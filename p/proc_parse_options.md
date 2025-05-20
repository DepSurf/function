# Function: <code>proc_parse_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_parse_options(char *options, struct pid_namespace *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff81279d60)
Location: fs/proc/root.c:51
Inline: False
Direct callers:
  - fs/proc/root.c:proc_mount
  - fs/proc/root.c:proc_remount
```
**Symbols:**

```
ffffffff81279d60-ffffffff81279e95: proc_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_parse_options(char *options, struct pid_namespace *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff812a6ca0)
Location: fs/proc/root.c:36
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/root.c:proc_remount
```
**Symbols:**

```
ffffffff812a6ca0-ffffffff812a6dda: proc_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_parse_options(char *options, struct pid_namespace *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff812bc580)
Location: fs/proc/root.c:36
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/root.c:proc_remount
```
**Symbols:**

```
ffffffff812bc580-ffffffff812bc6ba: proc_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_parse_options(char *options, struct pid_namespace *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff812c98f0)
Location: fs/proc/root.c:38
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/root.c:proc_remount
```
**Symbols:**

```
ffffffff812c98f0-ffffffff812c9a35: proc_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_parse_options(char *options, struct pid_namespace *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff812ee180)
Location: fs/proc/root.c:39
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/root.c:proc_remount
```
**Symbols:**

```
ffffffff812ee180-ffffffff812ee2c5: proc_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int proc_parse_options(char *options, struct pid_namespace *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:39
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/root.c:proc_remount
```
**Symbols:**

```
ffffffff8131b3c4-ffffffff8131b3d5: proc_parse_options.cold.1 (STB_LOCAL)
ffffffff8131b200-ffffffff8131b337: proc_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int proc_parse_options(char *options, struct pid_namespace *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:39
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/root.c:proc_remount
```
**Symbols:**

```
ffffffff81332454-ffffffff81332465: proc_parse_options.cold.1 (STB_LOCAL)
ffffffff81332290-ffffffff813323c7: proc_parse_options (STB_GLOBAL)
```
</details>
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
</ul>
