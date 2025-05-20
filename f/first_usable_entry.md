# Function: <code>first_usable_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81284180)
Location: fs/proc/proc_sysctl.c:347
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff81284180-ffffffff812841c9: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b1230)
Location: fs/proc/proc_sysctl.c:347
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff812b1230-ffffffff812b1276: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c6ac0)
Location: fs/proc/proc_sysctl.c:347
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff812c6ac0-ffffffff812c6b06: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d3c80)
Location: fs/proc/proc_sysctl.c:378
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff812d3c80-ffffffff812d3cc9: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f84b0)
Location: fs/proc/proc_sysctl.c:379
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff812f84b0-ffffffff812f84f9: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81326eee)
Location: fs/proc/proc_sysctl.c:379
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff81325b30-ffffffff81325b79: first_usable_entry.part.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133e0be)
Location: fs/proc/proc_sysctl.c:379
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff8133cce0-ffffffff8133cd29: first_usable_entry.part.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81364b40)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff81364b40-ffffffff81364b89: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137cdd0)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff8137cdd0-ffffffff8137ce19: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c88e8)
Location: fs/proc/proc_sysctl.c:352
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813da8d8)
Location: fs/proc/proc_sysctl.c:353
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
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
In fs/proc/proc_sysctl.c (ffffffff813e14b8)
Location: fs/proc/proc_sysctl.c:348
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
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
In fs/proc/proc_sysctl.c (ffffffff81432f8b)
Location: fs/proc/proc_sysctl.c:348
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
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
In fs/proc/proc_sysctl.c (ffffffff814ace58)
Location: fs/proc/proc_sysctl.c:373
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
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
In fs/proc/proc_sysctl.c (ffffffff815432a8)
Location: fs/proc/proc_sysctl.c:366
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
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
In fs/proc/proc_sysctl.c (ffffffff8157b6fb)
Location: fs/proc/proc_sysctl.c:360
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
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
In fs/proc/proc_sysctl.c (ffffffff815b3fab)
Location: fs/proc/proc_sysctl.c:362
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
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
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff800010449790)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffff800010449790-ffff8000104497f0: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c060ec14)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
c060ec14-c060ec64: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c0000000005604e0)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
c0000000005604e0-c000000000560580: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002df0d8)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffe0002df0d8-ffffffe0002df11a: first_usable_entry (STB_LOCAL)
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
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813753b0)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff813753b0-ffffffff813753f9: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81365e80)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff81365e80-ffffffff81365ec9: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81372e80)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff81372e80-ffffffff81372ec9: first_usable_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ctl_node *first_usable_entry(struct rb_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81386850)
Location: fs/proc/proc_sysctl.c:384
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff81386850-ffffffff81386899: first_usable_entry (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
