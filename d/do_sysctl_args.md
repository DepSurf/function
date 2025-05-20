# Function: <code>do_sysctl_args</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void do_sysctl_args();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1838
Inline: False
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff813c96e9-ffffffff813c96fc: do_sysctl_args.cold (STB_LOCAL)
ffffffff813c92f0-ffffffff813c938e: do_sysctl_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void do_sysctl_args();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1843
Inline: False
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff81bec078-ffffffff81bec08b: do_sysctl_args.cold (STB_LOCAL)
ffffffff813db2e0-ffffffff813db37e: do_sysctl_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void do_sysctl_args();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1847
Inline: False
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff81bde0d6-ffffffff81bde0e9: do_sysctl_args.cold (STB_LOCAL)
ffffffff813e2210-ffffffff813e22ae: do_sysctl_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void do_sysctl_args();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1847
Inline: False
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff81cc84ed-ffffffff81cc8500: do_sysctl_args.cold (STB_LOCAL)
ffffffff81433d20-ffffffff81433dbe: do_sysctl_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void do_sysctl_args();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1916
Inline: False
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff81e7b18f-ffffffff81e7b1a2: do_sysctl_args.cold (STB_LOCAL)
ffffffff814add20-ffffffff814addd1: do_sysctl_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_sysctl_args();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81544280)
Location: fs/proc/proc_sysctl.c:1915
Inline: False
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff81544280-ffffffff81544340: do_sysctl_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_sysctl_args();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157be80)
Location: fs/proc/proc_sysctl.c:1689
Inline: False
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff8157be80-ffffffff8157bf40: do_sysctl_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_sysctl_args();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b4790)
Location: fs/proc/proc_sysctl.c:1691
Inline: False
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff815b4790-ffffffff815b4850: do_sysctl_args (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
