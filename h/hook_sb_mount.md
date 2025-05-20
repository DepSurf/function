# Function: <code>hook_sb_mount</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hook_sb_mount(const const char * dev_name, const const struct path * path, const const char * type, const long unsigned int flags, const void * data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff815385c0)
Location: security/landlock/fs.c:466
Inline: False
```
**Symbols:**

```
ffffffff815385c0-ffffffff815385ef: hook_sb_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hook_sb_mount(const const char * dev_name, const const struct path * path, const const char * type, const long unsigned int flags, const void * data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81596db0)
Location: security/landlock/fs.c:466
Inline: False
```
**Symbols:**

```
ffffffff81596db0-ffffffff81596ddf: hook_sb_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hook_sb_mount(const const char * dev_name, const const struct path * path, const const char * type, const long unsigned int flags, const void * data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81639210)
Location: security/landlock/fs.c:1034
Inline: False
```
**Symbols:**

```
ffffffff81639210-ffffffff81639245: hook_sb_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hook_sb_mount(const const char * dev_name, const const struct path * path, const const char * type, const long unsigned int flags, const void * data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff816f07a0)
Location: security/landlock/fs.c:1049
Inline: False
```
**Symbols:**

```
ffffffff816f07a0-ffffffff816f07d5: hook_sb_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hook_sb_mount(const const char * dev_name, const const struct path * path, const const char * type, const long unsigned int flags, const void * data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8172ac40)
Location: security/landlock/fs.c:1049
Inline: False
```
**Symbols:**

```
ffffffff8172ac40-ffffffff8172ac75: hook_sb_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hook_sb_mount(const const char * dev_name, const const struct path * path, const const char * type, const long unsigned int flags, const void * data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176c750)
Location: security/landlock/fs.c:966
Inline: False
```
**Symbols:**

```
ffffffff8176c750-ffffffff8176c769: hook_sb_mount (STB_LOCAL)
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
