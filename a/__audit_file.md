# Function: <code>__audit_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81128d50)
Location: kernel/auditsc.c:1832
Inline: False
Direct callers:
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fchown
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fremovexattr
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff81128d50-ffffffff81128d68: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81130ee0)
Location: kernel/auditsc.c:1831
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff81130ee0-ffffffff81130ef8: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113ac50)
Location: kernel/auditsc.c:1836
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff8113ac50-ffffffff8113ac68: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113c260)
Location: kernel/auditsc.c:1845
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff8113c260-ffffffff8113c278: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81148fe0)
Location: kernel/auditsc.c:1845
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81148fe0-ffffffff81148ff8: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81157980)
Location: kernel/auditsc.c:1852
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81157980-ffffffff81157998: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81164980)
Location: kernel/auditsc.c:1838
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81164980-ffffffff81164998: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81171660)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81171660-ffffffff81171678: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117d4e0)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff8117d4e0-ffffffff8117d4f8: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81190730)
Location: kernel/auditsc.c:2073
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81190730-ffffffff81190748: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d950)
Location: kernel/auditsc.c:2090
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff8118d950-ffffffff8118d968: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118e8c0)
Location: kernel/auditsc.c:2087
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff8118e8c0-ffffffff8118e8d8: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b76d0)
Location: kernel/auditsc.c:2100
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff811b76d0-ffffffff811b76e8: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811ea4b0)
Location: kernel/auditsc.c:2391
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff811ea4b0-ffffffff811ea4d2: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812306d0)
Location: kernel/auditsc.c:2369
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff812306d0-ffffffff812306f2: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81247240)
Location: kernel/auditsc.c:2366
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81247240-ffffffff81247265: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812610b0)
Location: kernel/auditsc.c:2361
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff812610b0-ffffffff812610d5: __audit_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f23b0)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__arm64_sys_fremovexattr
  - fs/xattr.c:__arm64_sys_flistxattr
  - fs/xattr.c:__arm64_sys_fgetxattr
  - fs/xattr.c:__arm64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffff8000101f23b0-ffff8000101f23e4: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c04328dc)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
c04328dc-c0432904: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000266b70)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
c000000000266b70-c000000000266b94: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165ac6)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
**Symbols:**

```
ffffffe000165ac6-ffffffe000165af4: __audit_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81175b00)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81175b00-ffffffff81175b18: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81168ca0)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81168ca0-ffffffff81168cb8: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811738d0)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff811738d0-ffffffff811738e8: __audit_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __audit_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81181190)
Location: kernel/auditsc.c:2042
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81181190-ffffffff811811a8: __audit_file (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
