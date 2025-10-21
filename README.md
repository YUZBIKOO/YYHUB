local ReplicatedStorage = game:GetService("ReplicatedStorage")

-- Remote
local OpenCase = ReplicatedStorage.Events.OpenCase -- RemoteFunction 

while wait(0.3) do
    OpenCase:InvokeServer(
        "Gold",
        10
    )
end
