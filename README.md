404 (Not found
local DataStoreService = game:GetService("DataStoreService")
local myDataStore = DataStoreService:GetDataStore("PlayerXP")

-- Wrap in pcall to handle potential API downtime
local success, result = pcall(function()
    return myDataStore:GetAsync("User_12345")
end)

if success then
    print("Data loaded:", result)
else
    warn("Failed to load data:", result) -- result is the error message
end
end--- result as a error message 203---21
good--- result as  error 
local DataStoreService = game:GetService("DataStoreService")
local myDataStore = DataStoreService:GetDataStore("PlayerXP")

-- Wrap in pcall to handle potential API downtime
local success, result = pcall(function()
    return myDataStore:GetAsync("User_12345")
end)

if success then
    print("Data loaded:", result)
else
    warn("Failed to load data:", result) -- result is the error message
    end of shift local DataStoreService = game:GetService("DataStoreService")
local myDataStore = DataStoreService:GetDataStore("PlayerXP")

-- Wrap in pcall to handle potential API downtime
local success, result = pcall(function()
    return myDataStore:GetAsync("User_12345")
end)

if success then
    print("Data loaded:", result)
else
    warn("Failed to load data:", result) -- result is the error message
end
auscess for acesss 
