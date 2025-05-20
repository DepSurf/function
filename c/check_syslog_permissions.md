# Function: <code>check_syslog_permissions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d6ad0)
Location: kernel/printk/printk.c:495
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - fs/pstore/inode.c:pstore_unlink
  - fs/pstore/inode.c:pstore_file_open
```
**Symbols:**

```
ffffffff810d6ad0-ffffffff810d6b5d: check_syslog_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dbd10)
Location: kernel/printk/printk.c:605
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - fs/pstore/inode.c:pstore_unlink
  - fs/pstore/inode.c:pstore_file_open
```
**Symbols:**

```
ffffffff810dbd10-ffffffff810dbd9d: check_syslog_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2d30)
Location: kernel/printk/printk.c:603
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - fs/pstore/inode.c:pstore_unlink
  - fs/pstore/inode.c:pstore_file_open
```
**Symbols:**

```
ffffffff810e2d30-ffffffff810e2dbd: check_syslog_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e1e00)
Location: kernel/printk/printk.c:652
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_unlink
  - fs/pstore/inode.c:pstore_file_open
```
**Symbols:**

```
ffffffff810e1e00-ffffffff810e1e8b: check_syslog_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e9f00)
Location: kernel/printk/printk.c:652
Inline: False
```
**Symbols:**

```
ffffffff810e9f00-ffffffff810e9f8b: check_syslog_permissions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:656
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff810f21e0-ffffffff810f2245: check_syslog_permissions (STB_LOCAL)
ffffffff810f4e32-ffffffff810f4e60: check_syslog_permissions.cold.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:652
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff810fd930-ffffffff810fd995: check_syslog_permissions (STB_LOCAL)
ffffffff811005f2-ffffffff81100620: check_syslog_permissions.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:669
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff81105c70-ffffffff81105cdb: check_syslog_permissions (STB_LOCAL)
ffffffff81108dd2-ffffffff81108e00: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff81111ff0-ffffffff8111205b: check_syslog_permissions (STB_LOCAL)
ffffffff811151b2-ffffffff811151e0: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:691
Inline: False
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff8111d7a0-ffffffff8111d80d: check_syslog_permissions (STB_LOCAL)
ffffffff81120b8c-ffffffff81120bba: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:508
Inline: False
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff81118210-ffffffff8111827d: check_syslog_permissions (STB_LOCAL)
ffffffff81be119a-ffffffff81be11c8: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:521
Inline: False
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff81118850-ffffffff811188bd: check_syslog_permissions (STB_LOCAL)
ffffffff81bd321b-ffffffff81bd3249: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:516
Inline: False
Direct callers:
  - kernel/printk/printk.c:__ia32_sys_syslog
  - kernel/printk/printk.c:__x64_sys_syslog
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff81139090-ffffffff81139109: check_syslog_permissions (STB_LOCAL)
ffffffff81cac0f3-ffffffff81cac135: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:521
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff8115b9b0-ffffffff8115ba32: check_syslog_permissions (STB_LOCAL)
ffffffff81e5c5b8-ffffffff81e5c5fb: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:602
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff8118e380-ffffffff8118e42e: check_syslog_permissions (STB_LOCAL)
ffffffff820588ae-ffffffff820588c3: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:589
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff8119fce0-ffffffff8119fd8e: check_syslog_permissions (STB_LOCAL)
ffffffff820d716c-ffffffff820d7181: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:589
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff811aed40-ffffffff811aedee: check_syslog_permissions (STB_LOCAL)
ffffffff821b23b5-ffffffff821b23ca: check_syslog_permissions.cold (STB_LOCAL)
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
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010172358)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffff800010172358-ffff800010172404: check_syslog_permissions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c4f60)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
c03c4f60-c03c502c: check_syslog_permissions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cb820)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
c0000000001cb820-c0000000001cb918: check_syslog_permissions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010e6d8)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffe00010e6d8-ffffffe00010e784: check_syslog_permissions (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff8110a5d0-ffffffff8110a63b: check_syslog_permissions (STB_LOCAL)
ffffffff8110d792-ffffffff8110d7c0: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff810fb4b0-ffffffff810fb51b: check_syslog_permissions (STB_LOCAL)
ffffffff810fe4f2-ffffffff810fe520: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff811084c0-ffffffff8110852b: check_syslog_permissions (STB_LOCAL)
ffffffff8110b682-ffffffff8110b6b0: check_syslog_permissions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_syslog_permissions(int type, int source);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_open
```
**Symbols:**

```
ffffffff81113860-ffffffff811138cb: check_syslog_permissions (STB_LOCAL)
ffffffff81116b42-ffffffff81116b70: check_syslog_permissions.cold (STB_LOCAL)
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
