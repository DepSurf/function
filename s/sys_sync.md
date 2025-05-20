# Function: <code>sys_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812407a0)
Location: fs/sync.c:107
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff812407a0-ffffffff81240849: sys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81268ae0)
Location: fs/sync.c:107
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff81268ae0-ffffffff81268b89: sys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8127bac0)
Location: fs/sync.c:108
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff8127bac0-ffffffff8127bb69: sys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81288e30)
Location: fs/sync.c:108
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff81288e30-ffffffff81288ed9: sys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812ab970)
Location: fs/sync.c:109
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff812ab970-ffffffff812aba17: sys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int sys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c05ab764)
Location: fs/sync.c:123
Inline: False
```
**Symbols:**

```
c05ab764-c05ab784: sys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c0000000004d2c30)
Location: fs/sync.c:123
Inline: False
```
**Symbols:**

```
c0000000004d2c30-c0000000004d2c64: sys_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int sys_sync();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffe00028c680)
Location: fs/sync.c:123
Inline: False
```
**Symbols:**

```
ffffffe00028c680-ffffffe00028c6a4: sys_sync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
<b>Arch</b>
<ul>
</ul>
