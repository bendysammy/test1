--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.1.6) ~  Much Love, Ferib 

]]--

do do local v0=0;local v1;local v2;local v3;while true do if (v0==2) then v3:SetPrimaryPartCFrame(v2);v1:Destroy();v0=3;end if (v0==3) then workspace.h.c.Prompt.Triggered:Connect(function()local v5=0;local v6;local v7;local v8;local v9;local v10;local v11;local v12;local v13;local v14;local v15;local v16;local v17;local v18;local v19;local v20;local v21;local v22;local v23;local v24;local v25;while true do if (v5==2) then v14=nil;v15=nil;v16=nil;v17=nil;v5=3;end if (v5==0) then v6=0;v7=nil;v8=nil;v9=nil;v5=1;end if (v5==3) then v18=nil;v19=nil;v20=nil;v21=nil;v5=4;end if (v5==1) then local v34=0;while true do if (v34==2) then v5=2;break;end if (v34==1) then v12=nil;v13=nil;v34=2;end if (v34==0) then v10=nil;v11=nil;v34=1;end end end if (v5==4) then local v35=0;while true do if (v35==0) then v22=nil;v23=nil;v35=1;end if (v35==2) then v5=5;break;end if (v35==1) then v24=nil;v25=nil;v35=2;end end end if (v5==5) then while true do if (v6==3) then v13=v12.Character or v12.CharacterAdded:Wait();v14=v13:WaitForChild("Humanoid");v15=v13:WaitForChild("HumanoidRootPart");v16=v13:WaitForChild("RightUpperArm");v6=4;end if (v6==2) then local v44=0;local v45;while true do if (v44==0) then v45=0;while true do if (v45==1) then v11=game:GetService("UserInputService");v12=v10.LocalPlayer;v45=2;end if (v45==0) then local v77=0;while true do if (v77==1) then v45=1;break;end if (v77==0) then getgenv().v99=Enum.KeyCode.F4;v10=game:GetService("Players");v77=1;end end end if (2==v45) then v6=3;break;end end break;end end end if (v6==6) then local v46=0;while true do if (v46==1) then v22(v23);v10=game:GetService("Players");v46=2;end if (v46==2) then v6=7;break;end if (v46==0) then v23.v65="Crucifix";v23.v66=game.Players.LocalPlayer.Backpack;v46=1;end end end if (8==v6) then local v47=0;while true do if (0==v47) then v15=v13:WaitForChild("HumanoidRootPart");v24=Instance.new("BindableEvent");v47=1;end if (v47==2) then v6=9;break;end if (v47==1) then local v67=0;while true do if (v67==0) then v25=nil;function v25(v83)local v86=0;while true do if (v86==0) then wait(0.01);if ((v83:GetAttribute("IsCustomEntity")==true) and (v83:GetAttribute("ClonedByCrucifix")~=true)) then local v109=0;local v110;local v111;local v112;local v113;local v114;local v115;local v116;local v117;while true do if (v109==2) then v114=nil;v115=nil;v109=3;end if (3==v109) then v116=nil;v117=nil;v109=4;end if (v109==1) then v112=nil;v113=nil;v109=2;end if (0==v109) then v110=0;v111=nil;v109=1;end if (v109==4) then while true do if (3==v110) then v117=nil;while true do if (v111==3) then v117=true;game:GetService("RunService").RenderStepped:Connect(function()if v9 then if ((v83.Parent~=nil) and v83.PrimaryPart and v8(v83.PrimaryPart) and ((v15.Position-v83.PrimaryPart.Position).magnitude<=25)) then local v180=0;local v181;local v182;local v183;while true do if (v180==0) then v181=0;v182=nil;v180=1;end if (v180==1) then v183=nil;while true do if (v181==2) then v83:Destroy();v24:Fire(6,v182.RushNew);v181=3;end if (v181==3) then v183=v182:FindFirstChild("RushNew");if v183 then local v206=0;local v207;local v208;while true do if (v206==0) then v207=0;v208=nil;v206=1;end if (v206==1) then while true do if (v207==1) then local v215=0;while true do if (v215==0) then local v221=0;while true do if (v221==0) then for v227,v228 in pairs(v112:GetDescendants()) do local v229=0;while true do if (v229==0) then if v228:IsA("BasePart") then v228.v233=false;end if (v228.Name=="Beam") then v228.v234=v208;end break;end end end if  not v114 then local v231=0;while true do if (v231==0) then v112:SetPrimaryPartCFrame(v183.CFrame * CFrame.new(0, -3.5,0) * CFrame.Angles(math.rad(90),0,0));v114=true;break;end end end v221=1;end if (v221==1) then v215=1;break;end end end if (v215==1) then v207=2;break;end end end if (v207==2) then task.wait(1.35);if  not v116 then local v218=0;while true do if (v218==3) then game:GetService("Debris"):AddItem(v182,0);game:GetService("Debris"):AddItem(v112,0);break;end if (2==v218) then local v222=0;while true do if (0==v222) then task.wait(1.5);v117=false;v222=1;end if (v222==1) then v218=3;break;end end end if (v218==0) then local v223=0;while true do if (v223==0) then task.spawn(function()while task.wait() do if v112:FindFirstChild("Base") then v112.Base.v237=v112.Base.CFrame * CFrame.Angles(0,0,math.rad(0.5));end end end);task.spawn(function()while task.wait() do for v235,v236 in pairs(v112:GetDescendants()) do if (v236.Name=="Beam") then v236.TextureLength=v236.TextureLength + 0.035;end end end end);v223=1;end if (v223==1) then v218=1;break;end end end if (v218==1) then local v224=0;while true do if (0==v224) then game.TweenService:Create(v183,TweenInfo.new(6),{CFrame=v183.CFrame * CFrame.new(0,50,0)}):Play();v116=true;v224=1;end if (v224==1) then v218=2;break;end end end end end break;end if (v207==0) then local v216=0;local v217;while true do if (0==v216) then v217=0;while true do if (v217==1) then v207=1;break;end if (v217==0) then local v226=0;while true do if (v226==1) then v217=1;break;end if (0==v226) then v208=Instance.new("Attachment");v208.v232=v183;v226=1;end end end end break;end end end end break;end end end break;end if (v181==0) then local v200=0;while true do if (v200==0) then v182=v83:Clone();v182:SetAttribute("ClonedByCrucifix",true);v200=1;end if (v200==1) then v181=1;break;end end end if (v181==1) then local v201=0;while true do if (v201==1) then v181=2;break;end if (v201==0) then v182.RushNew.v209=true;v182.v210=v83.Parent;v201=1;end end end end break;end end end end end);break;end if (v111==2) then local v148=0;while true do if (v148==1) then v111=3;break;end if (v148==0) then local v161=0;while true do if (v161==0) then v115=false;v116=false;v161=1;end if (v161==1) then v148=1;break;end end end end end if (v111==0) then local v149=0;while true do if (v149==0) then local v162=0;while true do if (v162==0) then v112=game:GetObjects("rbxassetid://"   .. getgenv().TheCircleWithTheChains)[1];v112.v184=workspace;v162=1;end if (1==v162) then v149=1;break;end end end if (v149==1) then v111=1;break;end end end if (v111==1) then local v150=0;while true do if (1==v150) then v111=2;break;end if (0==v150) then v113=true;v114=false;v150=1;end end end end break;end if (v110==0) then local v140=0;while true do if (v140==1) then v110=1;break;end if (v140==0) then v111=0;v112=nil;v140=1;end end end if (v110==2) then v115=nil;v116=nil;v110=3;end if (1==v110) then v113=nil;v114=nil;v110=2;end end break;end end elseif (v83.Name=="Lookman") then local v122=v83;task.spawn(function()local v134=0;local v135;local v136;local v137;local v138;while true do if (v134==0) then v135=0;v136=nil;v134=1;end if (v134==1) then v137=nil;v138=nil;v134=2;end if (v134==2) then while true do if (3==v135) then function v138(v157)local v163=0;local v164;local v165;local v166;local v167;while true do if (v163==0) then v164=0;v165=nil;v163=1;end if (v163==2) then while true do if (v164==0) then local v194=0;while true do if (v194==0) then v165,v166,v167=v157:ToOrientation();return Vector3.new(math.deg(v165),math.deg(v166),math.deg(v167));end end end end break;end if (v163==1) then v166=nil;v167=nil;v163=2;end end end while (v122.Parent~=nil) and (v122.Core.Attachment.Eyes.Enabled==true) do local v158=0;local v159;local v160;while true do if (1==v158) then while true do if (v159==0) then v160=0;while true do if (v160==0) then v137.v199=v138(CFrame.lookAt(v137.Position,v136) * CFrame.Angles(0,math.pi,0));task.wait();break;end end break;end end break;end if (v158==0) then v159=0;v160=nil;v158=1;end end end break;end if (v135==2) then v137=game.Players.LocalPlayer.Character.Collision;v138=nil;v135=3;end if (0==v135) then local v155=0;while true do if (v155==0) then repeat task.wait();until v8(v122.Core) and v9 and (v122.Core.Attachment.Eyes.Enabled==true)v136=v122.Core.Position;v155=1;end if (v155==1) then v135=1;break;end end end if (v135==1) then local v156=0;while true do if (v156==0) then v24:Fire(18.364,v122.Core);task.spawn(function()local v185=0;local v186;while true do if (v185==0) then v186=0;while true do if (v186==4) then for v204,v205 in pairs(v122:GetDescendants()) do if v205:IsA("PointLight") then v205.v211=false;end end game:GetService("TweenService"):Create(v122.Core,TweenInfo.new(v122.Core.Scream.TimeLength,Enum.EasingStyle.Sine,Enum.EasingDirection.InOut),{CFrame=CFrame.new(v122.Core.CFrame.X,v122.Core.CFrame.Y-12,v122.Core.CFrame.Z)}):Play();break;end if (v186==1) then wait(5);v122.Core.Initiate:Stop();v186=2;end if (v186==3) then v21.MainGame.camShaker:ShakeOnce(8,8,v122.Core.Scream.TimeLength,0.15);(v122.Core:FindFirstChild('"whisper"') or v122.Core:FindFirstChild('"Ambience"')):Stop();v186=4;end if (v186==2) then local v202=0;while true do if (v202==0) then for v212=1,3 do local v213=0;local v214;while true do if (0==v213) then v214=0;while true do if (v214==1) then local v219=0;while true do if (v219==0) then v21.MainGame.camShaker:ShakeOnce(8,8,1.3,0.15);delay(v122.Core.Repent.TimeLength,function()v122.Core.Attachment.Angry.v230=false;end);v219=1;end if (v219==1) then v214=2;break;end end end if (v214==0) then local v220=0;while true do if (v220==0) then v122.Core.Repent:Play();v122.Core.Attachment.Angry.v225=true;v220=1;end if (v220==1) then v214=1;break;end end end if (v214==2) then wait(4);break;end end break;end end end v122.Core.Scream:Play();v202=1;end if (1==v202) then v186=3;break;end end end if (v186==0) then local v203=0;while true do if (v203==0) then v122:SetAttribute("Killing",true);v21.MainGame.camShaker:ShakeOnce(10,10,5,0.15);v203=1;end if (v203==1) then v186=1;break;end end end end break;end end end);v156=1;end if (v156==1) then v135=2;break;end end end end break;end end end);elseif ((v83.Name=="Shade") and (v83.Parent==workspace.CurrentCamera) and (v83:GetAttribute("ClonedByCrucifix")==nil)) then task.spawn(function()local v141=0;local v142;local v143;local v144;local v145;while true do if (2==v141) then while true do if (v142==5) then wait(8.2);game:GetService("Debris"):AddItem(v143,0);game.ReplicatedStorage.Bricks.ShadeResult:FireServer();break;end if (v142==4) then v143.Burst:Stop();v143.Burst:Play();v145.v168=Color3.fromRGB(215,253,255);game:GetService("TweenService"):Create(v143,TweenInfo.new(6),{CFrame=CFrame.new(v143.CFrame.X,v143.CFrame.Y-12,v143.CFrame.Z)}):Play();v142=5;end if (v142==1) then v143.v169=true;v83:Remove();v24:Fire(13,v83);v21.MainGame.camShaker:ShakeOnce(40,10,5,0.15);v142=2;end if (v142==3) then v145=game.Lighting['Ambience_Shade'];game:GetService("TweenService"):Create(v145,TweenInfo.new(1),{}):Play();wait(5);v143.Burst.v170=0.5;v142=4;end if (v142==0) then repeat task.wait();until v8(v83) and ((v15.Position-v83.Position).Magnitude<=12.5) and v9 v143=v83:Clone();v143.v171=v83.CFrame;v143.v172=v83.Parent;v142=1;end if (v142==2) then local v173=0;while true do if (v173==2) then v142=3;break;end if (v173==1) then v144={};v145=nil;v173=2;end if (v173==0) then for v190,v191 in pairs(v143:GetDescendants()) do if v191:IsA("SpotLight") then game:GetService("TweenService"):Create(v191,TweenInfo.new(5),{Brightness=v191.Brightness * 5}):Play();elseif (v191:IsA("Sound") and (v191.Name~="Burst")) then game:GetService("TweenService"):Create(v191,TweenInfo.new(5),{Volume=0}):Play();elseif v191:IsA("TouchTransmitter") then v191:Destroy();end end for v192,v193 in pairs(v143:GetDescendants()) do if v193:IsA("ParticleEmitter") then v193.v195=ColorSequence.new({ColorSequenceKeypoint.new(0,Color3.fromRGB(255,0,4)),ColorSequenceKeypoint.new(0.48,Color3.fromRGB(182,0,3)),ColorSequenceKeypoint.new(1,Color3.fromRGB(255,0,4))});end end v173=1;end end end end break;end if (v141==0) then v142=0;v143=nil;v141=1;end if (v141==1) then v144=nil;v145=nil;v141=2;end end end);end break;end end end v67=1;end if (v67==1) then v47=2;break;end end end end end if (v6==1) then local v48=0;local v49;while true do if (v48==0) then v49=0;while true do if (v49==2) then v6=2;break;end if (v49==1) then function v8(v84)local v87=0;local v88;local v89;local v90;local v91;local v92;local v93;while true do if (v87==1) then local v106=0;while true do if (v106==1) then v87=2;break;end if (v106==0) then v90=nil;v91=nil;v106=1;end end end if (v87==3) then while true do if (v88==3) then if v91 then if (v93 and ((v93 and v93.Instance).Parent==game.Players.LocalPlayer.Character)) then return true;end end break;end if (v88==1) then local v118=0;local v119;while true do if (v118==0) then v119=0;while true do if (v119==0) then v92=RaycastParams.new();v92.v146=Enum.RaycastFilterType.Blacklist;v119=1;end if (1==v119) then v88=2;break;end end break;end end end if (2==v88) then local v120=0;while true do if (v120==1) then v88=3;break;end if (0==v120) then local v139=0;while true do if (v139==1) then v120=1;break;end if (v139==0) then v92.v147={v84};v93=workspace:Raycast(v84.Position,game.Players.LocalPlayer.Character.UpperTorso.Position-v84.Position,v92);v139=1;end end end end end if (v88==0) then local v121=0;while true do if (v121==1) then v88=1;break;end if (0==v121) then v89,v90=workspace.CurrentCamera:WorldToViewportPoint(v84.Position);v91=v90 and (v89.Z>0);v121=1;end end end end break;end if (v87==2) then v92=nil;v93=nil;v87=3;end if (v87==0) then v88=0;v89=nil;v87=1;end end end v9=false;v49=2;end if (0==v49) then local v78=0;while true do if (v78==1) then v49=1;break;end if (0==v78) then v7.CreateItem(exampleTool,{Title="Crucifix",Desc="The Devils Nightmare",Image="https://static.wikia.nocookie.net/doors-game/images/8/88/Icon_crucifix2.png/revision/latest/scale-to-width-down/350?cb=20220728033038",Price="300",Stack=1});v8=nil;v78=1;end end end end break;end end end if (v6==7) then local v50=0;while true do if (v50==2) then v6=8;break;end if (v50==1) then v13=v12.Character or v12.CharacterAdded:Wait();v14=v13:WaitForChild("Humanoid");v50=2;end if (0==v50) then v11=game:GetService("UserInputService");v12=v10.LocalPlayer;v50=1;end end end if (v6==9) then workspace.ChildAdded:Connect(v25);workspace.CurrentCamera.ChildAdded:Connect(v25);for v58,v59 in pairs(workspace:GetChildren()) do v25(v59);end v24.Event:Connect(function(v60,v61)local v62=0;local v63;local v64;while true do if (v62==1) then local v72=0;while true do if (2==v72) then v62=2;break;end if (v72==1) then task.wait(v60);v64.v94=false;v72=2;end if (v72==0) then v64.v95=CFrame.lookAt(v23.Handle.Position,v61.Position);v64.v96=true;v72=1;end end end if (0==v62) then v63=game:GetObjects("rbxassetid://"   .. getgenv().CrucifixThatShowsWhenUsed)[1];v63.v73=workspace;v64=v63.Handle;v21.MainGame.camShaker:ShakeOnce(35,25,0.15,0.15);v62=1;end if (v62==2) then v64.v74=true;task.wait(0.5);v63:Remove();break;end end end);break;end if (v6==5) then local v51=0;while true do if (v51==1) then local v68=0;while true do if (v68==0) then function v22(v85)local v97=0;local v98;while true do if (0==v97) then v98=0;while true do if (v98==0) then v85.Equipped:Connect(function()local v129=0;local v130;local v131;while true do if (v129==0) then v130=0;v131=nil;v129=1;end if (v129==1) then while true do if (v130==0) then v131=0;while true do if (v131==1) then local v174=0;while true do if (v174==0) then local v187=0;while true do if (1==v187) then v174=1;break;end if (v187==0) then for v197,v198 in next,v14:GetPlayingAnimationTracks() do v198:Stop();end v16.v196="R_Arm";v187=1;end end end if (1==v174) then v131=2;break;end end end if (v131==2) then local v175=0;while true do if (v175==1) then v131=3;break;end if (v175==0) then v17.v188="L_Arm";v16.RightShoulder.v189=v18 * CFrame.Angles(math.rad( -90),math.rad( -15),0);v175=1;end end end if (3==v131) then v17.LeftShoulder.v176=v19 * CFrame.new( -0.2, -0.3, -0.5) * CFrame.Angles(math.rad( -125),math.rad(25),math.rad(25));break;end if (v131==0) then local v177=0;while true do if (v177==1) then v131=1;break;end if (v177==0) then v9=true;v13:SetAttribute("Hiding",true);v177=1;end end end end break;end end break;end end end);v85.Unequipped:Connect(function()local v132=0;local v133;while true do if (0==v132) then v133=0;while true do if (v133==2) then v16.RightShoulder.v151=v18;v17.LeftShoulder.v152=v19;break;end if (v133==1) then local v153=0;while true do if (1==v153) then v133=2;break;end if (v153==0) then v16.v178="RightUpperArm";v17.v179="LeftUpperArm";v153=1;end end end if (v133==0) then local v154=0;while true do if (v154==1) then v133=1;break;end if (v154==0) then v9=false;v13:SetAttribute("Hiding",nil);v154=1;end end end end break;end end end);break;end end break;end end end v23=game:GetObjects("rbxassetid://"   .. getgenv().TheTool)[1];v68=1;end if (v68==1) then v51=2;break;end end end if (v51==2) then v6=6;break;end if (v51==0) then v21={MainGame=require(v12.PlayerGui.MainUI.Initiator.Main_Game),SeekIntro=require(v12.PlayerGui.MainUI.Initiator.Main_Game.RemoteListener.Cutscenes.SeekIntro)};v22=nil;v51=1;end end end if (v6==0) then local v52=0;while true do if (v52==2) then v6=1;break;end if (v52==0) then local v69=0;while true do if (v69==0) then getgenv().v79="11747232253";getgenv().v80="11734246120";v69=1;end if (v69==1) then v52=1;break;end end end if (v52==1) then local v70=0;while true do if (v70==0) then getgenv().v81="11656343590";v7=loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors/Custom%20Shop%20Items/Source.lua"))();v70=1;end if (v70==1) then v52=2;break;end end end end end if (4==v6) then local v53=0;local v54;while true do if (v53==0) then v54=0;while true do if (0==v54) then v17=v13:WaitForChild("LeftUpperArm");v18=v16.RightShoulder.C1;v54=1;end if (1==v54) then local v82=0;while true do if (v82==1) then v54=2;break;end if (v82==0) then v19=v17.LeftShoulder.C1;v20={Functions=loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Functions.lua"))(),CustomShop=loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors/Custom%20Shop%20Items/Source.lua"))()};v82=1;end end end if (v54==2) then v6=5;break;end end break;end end end end break;end end end);workspace.h.Farmer.Prompt.Triggered:Connect(function()local v26=0;local v27;local v28;local v29;local v30;local v31;local v32;local v33;while true do if (v26==2) then v32.v36="rbxassetid://3034291703";v33=game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(v32);v31.Equipped:Connect(function()local v40=0;local v41;while true do if (v40==0) then v41=0;while true do if (v41==1) then v33:Play();break;end if (v41==0) then local v75=0;local v76;while true do if (v75==0) then v76=0;while true do if (v76==1) then v41=1;break;end if (v76==0) then v33.v107=Enum.AnimationPriority.Movement;v33.v108=true;v76=1;end end break;end end end end break;end end end);v30.InputBegan:Connect(function(v39)local v42=0;local v43;while true do if (v42==0) then v43=0;while true do if (v43==0) then if (v31.Parent==game.Players.LocalPlayer.Character) then if (v39.UserInputType==Enum.UserInputType.MouseButton1) then local v100=0;local v101;local v102;local v103;local v104;local v105;while true do if (v100==0) then v101=0;v102=nil;v100=1;end if (v100==1) then v103=nil;v104=nil;v100=2;end if (2==v100) then v105=nil;while true do if (v101==4) then wait(10);v102:Destroy();break;end if (v101==2) then v105.v123=v104;v102.v124=game.Workspace;v102.v125=v31.BulletPart.CFrame;v101=3;end if (v101==3) then local v126=0;while true do if (v126==1) then v105:Destroy();v101=4;break;end if (v126==0) then v31.Handle.fire:Play();wait(1);v126=1;end end end if (v101==0) then v102=LoadCustomInstance("rbxassetid://11773933852");v103=v31.BulletPart;v104=Instance.new("Attachment",v102);v101=1;end if (v101==1) then v105=Instance.new("LinearVelocity",v104);v105.v127=math.huge;v105.v128=v103.CFrame.lookVector * 100;v101=2;end end break;end end end end v31.Unequipped:Connect(function()if v33 then v33:Stop();end end);break;end end break;end end end);break;end if (v26==0) then local v37=0;while true do if (v37==2) then v26=1;break;end if (v37==1) then v29=game:GetObjects("rbxassetid://11772300157")[1];v29.v55=game.Players.LocalPlayer.Backpack;v37=2;end if (v37==0) then v27=loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Functions.lua"))();v28=loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors/Custom%20Shop%20Items/Source.lua"))();v37=1;end end end if (v26==1) then local v38=0;while true do if (v38==2) then v26=2;break;end if (v38==0) then local v56=0;while true do if (v56==0) then v30=game:GetService("UserInputService");v31=v29;v56=1;end if (v56==1) then v38=1;break;end end end if (v38==1) then local v57=0;while true do if (0==v57) then v32=Instance.new("Animation");v32.v71="M249Idle";v57=1;end if (v57==1) then v38=2;break;end end end end end end end);break;end if (v0==1) then v3=game:GetObjects("rbxassetid://11773652671")[1];v3.v4=workspace;v0=2;end if (v0==0) then v1=workspace.CurrentRooms[game.ReplicatedStorage.GameData.LatestRoom.Value]:FindFirstChild("FakeDoor_Hotel",true);v2=v1.FakeDoor.CFrame;v0=1;end end end end
