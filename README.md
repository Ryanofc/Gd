for _, obj in pairs(workspace:GetDescendants()) do
	if obj:IsA("Part") and obj.Name:lower():find("sell") then
		print("Possível barraca de venda encontrada:", obj:GetFullName())
	end
end
