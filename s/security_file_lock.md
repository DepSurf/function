# Function: <code>security_file_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133df20)
Location: security/security.c:820
Inline: False
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff8133df20-ffffffff8133df6f: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373580)
Location: security/security.c:842
Inline: False
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff81373580-ffffffff813735cf: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389eb0)
Location: security/security.c:863
Inline: False
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff81389eb0-ffffffff81389eff: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f2b0)
Location: security/security.c:1475
Inline: False
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff8139f2b0-ffffffff8139f2ff: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4df0)
Location: security/security.c:1433
Inline: False
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff813c4df0-ffffffff813c4e45: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f50a0)
Location: security/security.c:959
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff813f50a0-ffffffff813f50e4: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814104e0)
Location: security/security.c:1495
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff814104e0-ffffffff81410524: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dc40)
Location: security/security.c:1514
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8143dc40-ffffffff8143dc8d: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457720)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff81457720-ffffffff81457764: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aa520)
Location: security/security.c:1729
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff814aa520-ffffffff814aa564: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7b30)
Location: security/security.c:1731
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff814c7b30-ffffffff814c7b74: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce160)
Location: security/security.c:1781
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff814ce160-ffffffff814ce1a4: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526f10)
Location: security/security.c:1789
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff81526f10-ffffffff81526f54: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bbb30)
Location: security/security.c:1794
Inline: False
Direct callers:
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff815bbb30-ffffffff815bbb8d: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81667930)
Location: security/security.c:1836
Inline: False
Direct callers:
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff81667930-ffffffff8166798d: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169ff50)
Location: security/security.c:2872
Inline: False
Direct callers:
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff8169ff50-ffffffff8169ffad: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dc840)
Location: security/security.c:2950
Inline: False
Direct callers:
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff816dc840-ffffffff816dc89d: security_file_lock (STB_GLOBAL)
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
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543350)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/locks.c:__arm64_sys_flock
```
**Symbols:**

```
ffff800010543350-ffff8000105433b0: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f92b4)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/locks.c:__se_sys_flock
```
**Symbols:**

```
c06f92b4-c06f9310: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000697200)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/locks.c:__se_sys_flock
```
**Symbols:**

```
c000000000697200-c0000000006972bc: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f8f4)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/locks.c:__se_sys_flock
```
**Symbols:**

```
ffffffe00039f8f4-ffffffe00039f938: security_file_lock (STB_GLOBAL)
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
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144fd00)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8144fd00-ffffffff8144fd44: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440750)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff81440750-ffffffff81440794: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144bda0)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8144bda0-ffffffff8144bde4: security_file_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_file_lock(struct file *file, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463170)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff81463170-ffffffff814631b4: security_file_lock (STB_GLOBAL)
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
