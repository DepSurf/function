# Function: <code>new_dir</code>

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
In fs/proc/proc_sysctl.c (ffffffff81285d6e)
Location: fs/proc/proc_sysctl.c:878
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
In fs/proc/proc_sysctl.c (ffffffff812b2e7c)
Location: fs/proc/proc_sysctl.c:884
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
In fs/proc/proc_sysctl.c (ffffffff812c86cc)
Location: fs/proc/proc_sysctl.c:890
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
In fs/proc/proc_sysctl.c (ffffffff812d5add)
Location: fs/proc/proc_sysctl.c:937
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
In fs/proc/proc_sysctl.c (ffffffff812fa31d)
Location: fs/proc/proc_sysctl.c:938
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
In fs/proc/proc_sysctl.c (ffffffff8132748b)
Location: fs/proc/proc_sysctl.c:940
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
In fs/proc/proc_sysctl.c (ffffffff8133e615)
Location: fs/proc/proc_sysctl.c:939
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
In fs/proc/proc_sysctl.c (ffffffff81366974)
Location: fs/proc/proc_sysctl.c:964
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
In fs/proc/proc_sysctl.c (ffffffff8137ec04)
Location: fs/proc/proc_sysctl.c:964
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ctl_dir *new_dir(struct ctl_table_set *set, const char *name, int namelen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c7830)
Location: fs/proc/proc_sysctl.c:947
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:get_subdir
```
**Symbols:**

```
ffffffff813c7830-ffffffff813c7937: new_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ctl_dir *new_dir(struct ctl_table_set *set, const char *name, int namelen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813d9720)
Location: fs/proc/proc_sysctl.c:947
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:get_subdir
```
**Symbols:**

```
ffffffff813d9720-ffffffff813d9827: new_dir (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff813e1b4d)
Location: fs/proc/proc_sysctl.c:945
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
In fs/proc/proc_sysctl.c (ffffffff8143365d)
Location: fs/proc/proc_sysctl.c:945
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
In fs/proc/proc_sysctl.c (ffffffff814ad579)
Location: fs/proc/proc_sysctl.c:970
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ctl_dir *new_dir(struct ctl_table_set *set, const char *name, int namelen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81541bd0)
Location: fs/proc/proc_sysctl.c:963
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff81541bd0-ffffffff81541cc7: new_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ctl_dir *new_dir(struct ctl_table_set *set, const char *name, int namelen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81579ed0)
Location: fs/proc/proc_sysctl.c:956
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
```
**Symbols:**

```
ffffffff81579ed0-ffffffff81579ff3: new_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ctl_dir *new_dir(struct ctl_table_set *set, const char *name, int namelen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b27e0)
Location: fs/proc/proc_sysctl.c:948
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
```
**Symbols:**

```
ffffffff815b27e0-ffffffff815b28f5: new_dir (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffff80001044bf04)
Location: fs/proc/proc_sysctl.c:964
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
In fs/proc/proc_sysctl.c (c0610b80)
Location: fs/proc/proc_sysctl.c:964
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
In fs/proc/proc_sysctl.c (c000000000563874)
Location: fs/proc/proc_sysctl.c:964
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
Location: fs/proc/proc_sysctl.c:964
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
In fs/proc/proc_sysctl.c (ffffffff813771e4)
Location: fs/proc/proc_sysctl.c:964
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
In fs/proc/proc_sysctl.c (ffffffff81367cb4)
Location: fs/proc/proc_sysctl.c:964
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
In fs/proc/proc_sysctl.c (ffffffff81374cb4)
Location: fs/proc/proc_sysctl.c:964
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
In fs/proc/proc_sysctl.c (ffffffff813886bf)
Location: fs/proc/proc_sysctl.c:964
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
