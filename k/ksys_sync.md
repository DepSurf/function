# Function: <code>ksys_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812d2730)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - fs/sync.c:__x64_sys_sync
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff812d2730-ffffffff812d27d5: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812e7b10)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - fs/sync.c:__x64_sys_sync
```
**Symbols:**

```
ffffffff812e7b10-ffffffff812e7bb5: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813063d0)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__x64_sys_sync
```
**Symbols:**

```
ffffffff813063d0-ffffffff81306475: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81319450)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__x64_sys_sync
```
**Symbols:**

```
ffffffff81319450-ffffffff813194f5: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813532a0)
Location: fs/sync.c:110
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__do_sys_sync
```
**Symbols:**

```
ffffffff813532a0-ffffffff81353345: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8135fb80)
Location: fs/sync.c:110
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__do_sys_sync
```
**Symbols:**

```
ffffffff8135fb80-ffffffff8135fc25: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81366610)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__do_sys_sync
```
**Symbols:**

```
ffffffff81366610-ffffffff813666b5: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813b5160)
Location: fs/sync.c:110
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__do_sys_sync
```
**Symbols:**

```
ffffffff813b5160-ffffffff813b5205: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8143a360)
Location: fs/sync.c:97
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__do_sys_sync
```
**Symbols:**

```
ffffffff8143a360-ffffffff8143a404: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814c8780)
Location: fs/sync.c:97
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__do_sys_sync
```
**Symbols:**

```
ffffffff814c8780-ffffffff814c8824: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814fe9c0)
Location: fs/sync.c:97
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__do_sys_sync
```
**Symbols:**

```
ffffffff814fe9c0-ffffffff814fea64: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff815335c0)
Location: fs/sync.c:97
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__do_sys_sync
```
**Symbols:**

```
ffffffff815335c0-ffffffff81533664: ksys_sync (STB_GLOBAL)
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
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffff8000103d0410)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__arm64_sys_sync
```
**Symbols:**

```
ffff8000103d0410-ffff8000103d04cc: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c05ab690)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:sys_sync
```
**Symbols:**

```
c05ab690-c05ab764: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c0000000004d2b20)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:sys_sync
```
**Symbols:**

```
c0000000004d2b20-c0000000004d2c24: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffe00028c5da)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - fs/sync.c:sys_sync
```
**Symbols:**

```
ffffffe00028c5da-ffffffe00028c680: ksys_sync (STB_GLOBAL)
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
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81311a30)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__x64_sys_sync
```
**Symbols:**

```
ffffffff81311a30-ffffffff81311ad5: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81302640)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__x64_sys_sync
```
**Symbols:**

```
ffffffff81302640-ffffffff813026e5: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8130f820)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__x64_sys_sync
```
**Symbols:**

```
ffffffff8130f820-ffffffff8130f8c5: ksys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ksys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81321020)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/main.c:ksys_sync_helper
  - fs/sync.c:__x64_sys_sync
```
**Symbols:**

```
ffffffff81321020-ffffffff813210c5: ksys_sync (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
