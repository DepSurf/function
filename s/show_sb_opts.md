# Function: <code>show_sb_opts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff8124e9c0)
Location: fs/proc_namespace.c:42
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_mountinfo
```
**Symbols:**

```
ffffffff8124e9c0-ffffffff8124ea1d: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff81277140)
Location: fs/proc_namespace.c:42
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81277140-ffffffff8127719d: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff8128ae30)
Location: fs/proc_namespace.c:42
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff8128ae30-ffffffff8128ae8d: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff81297c30)
Location: fs/proc_namespace.c:44
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81297c30-ffffffff81297c8d: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff812baf10)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812baf10-ffffffff812baf6d: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff812e3aa0)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812e3aa0-ffffffff812e3afd: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff812f8720)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812f8720-ffffffff812f877d: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff81318d50)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81318d50-ffffffff81318dae: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff8132bb90)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff8132bb90-ffffffff8132bbee: show_sb_opts (STB_LOCAL)
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
In fs/proc_namespace.c (ffffffff81365a2a)
Location: fs/proc_namespace.c:45
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
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
In fs/proc_namespace.c (ffffffff813728fa)
Location: fs/proc_namespace.c:45
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
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
In fs/proc_namespace.c (ffffffff813792ab)
Location: fs/proc_namespace.c:45
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
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
In fs/proc_namespace.c (ffffffff813c5e0b)
Location: fs/proc_namespace.c:45
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
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
In fs/proc_namespace.c (ffffffff8144d09c)
Location: fs/proc_namespace.c:45
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
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
In fs/proc_namespace.c (ffffffff814db65c)
Location: fs/proc_namespace.c:45
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
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
In fs/proc_namespace.c (ffffffff8150fbfc)
Location: fs/proc_namespace.c:45
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
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
In fs/proc_namespace.c (ffffffff815440f3)
Location: fs/proc_namespace.c:45
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
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
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffff8000103e7268)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffff8000103e7268-ffff8000103e72e0: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (c05beea0)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
c05beea0-c05bef0c: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (c0000000004ed780)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
c0000000004ed780-c0000000004ed824: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffe00029c24e)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffe00029c24e-ffffffe00029c2b0: show_sb_opts (STB_LOCAL)
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
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff81324170)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81324170-ffffffff813241ce: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff81314d10)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81314d10-ffffffff81314d6e: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff81321c40)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81321c40-ffffffff81321c9e: show_sb_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int show_sb_opts(struct seq_file *m, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc_namespace.c (ffffffff813339a0)
Location: fs/proc_namespace.c:45
Inline: False
Direct callers:
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff813339a0-ffffffff813339fe: show_sb_opts (STB_LOCAL)
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
