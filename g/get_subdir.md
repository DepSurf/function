# Function: <code>get_subdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81285b9f)
Location: fs/proc/proc_sysctl.c:916
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b2c9f)
Location: fs/proc/proc_sysctl.c:922
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c84ef)
Location: fs/proc/proc_sysctl.c:928
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d5937)
Location: fs/proc/proc_sysctl.c:975
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812fa177)
Location: fs/proc/proc_sysctl.c:976
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81327337)
Location: fs/proc/proc_sysctl.c:978
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133e509)
Location: fs/proc/proc_sysctl.c:977
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813668b1)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137eb41)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct ctl_dir *get_subdir(struct ctl_dir *dir, const char *name, int namelen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:985
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff813c8410-ffffffff813c867d: get_subdir (STB_LOCAL)
ffffffff813c96de-ffffffff813c96e9: get_subdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct ctl_dir *get_subdir(struct ctl_dir *dir, const char *name, int namelen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:985
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff813da400-ffffffff813da66d: get_subdir (STB_LOCAL)
ffffffff81bec06d-ffffffff81bec078: get_subdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e19c2)
Location: fs/proc/proc_sysctl.c:983
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814334d2)
Location: fs/proc/proc_sysctl.c:983
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814ad3fc)
Location: fs/proc/proc_sysctl.c:1007
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8154387c)
Location: fs/proc/proc_sysctl.c:1000
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157ad6f)
Location: fs/proc/proc_sysctl.c:993
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b364f)
Location: fs/proc/proc_sysctl.c:985
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044bd3c)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c06109e8)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c0000000005636b4)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e0fe6)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81377121)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81367bf1)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81374bf1)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81388602)
Location: fs/proc/proc_sysctl.c:1002
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
