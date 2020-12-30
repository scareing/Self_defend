# Self_defend

* ProtectSelf
> 通过设置DACL安全描述符，从而创建用户权限无法结束的进程。

* Self_defend
> 通过CreateRemoteThread，远程注入shellcode，hook：AdjustTokenPrivileges，RtlSetDaclSecurityDescriptor，TerminateProcess，从而完成管理员权限的进程保护。
