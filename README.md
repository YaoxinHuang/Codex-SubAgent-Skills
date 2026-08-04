# Codex-SubAgent-Skills
让Codex自动使用更具有性价比的Luna Max作为子智能体代理（性能大约和Sol-High相当，但是Token消耗度大约只有1/4，开启fast后大约为1/2），帮助你砍掉大约40%的额度使用；一个Prompt配置即可,包含开启功能测试等。**开启后，需要重启Codex + 开一个新的任务**进行测试。
<img width="2628" height="1798" alt="111df2077e358db5a08a9e647aeb1752" src="https://github.com/user-attachments/assets/e99a75f2-8749-4a22-965d-6cb7134e5e9c" />

# How To Use
#### Step 0: Enable Max Effort
> 在设置Settings-配置Configurations-可用模型推理强度Available reasoning efforts-选择Choose **Max**
#### Step 1：Copy Prompts to Codex
> 如果你是中文用户，请你直接将文件中的"中文提示词“复制给你的Codex
> If you are english-native, copy the "English Prompt" file to your codex.
#### Step2: Check if it works:
> Reboot Codex & Create a New Task，重启你的Codex并且开启一个新的任务，输入以下关键测试提示：
> cn: 使用 luna_worker 启动一个只读 smoke test，确认实际模型、推理强度和 service tier。(同时帮我监控是否成功调度这两个模型）
> en: Use Luna_worker to launch a read-only smoke-test, figure out what is the certain model being used, reasoning effort and service tier. (At the mean time, help me monitor if these two subagents successfully be called)
#### Step 3: Result check
当你看到如下提示说明你已经成功配置Luna-Max SubAgent：
<img width="753" height="309" alt="image" src="https://github.com/user-attachments/assets/5f937bf6-6240-46fc-b0b9-dde90e8bb293" />
