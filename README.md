local Params = {
	RepoURL = "https://raw.githubusercontent.com/richardsmallsgit-tech/Utilities/tree/main/Syn/",
	SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {}
synsaveinstance(Options)
