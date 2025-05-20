# Function: <code>hook_file_open</code>

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
int hook_file_open(const struct file * file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81538890)
Location: security/landlock/fs.c:657
Inline: False
```
**Symbols:**

```
ffffffff81538890-ffffffff81538913: hook_file_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hook_file_open(const struct file * file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81597340)
Location: security/landlock/fs.c:657
Inline: False
```
**Symbols:**

```
ffffffff81597340-ffffffff815973ef: hook_file_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hook_file_open(const struct file * file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1163
Inline: False
```
**Symbols:**

```
ffffffff8163ae60-ffffffff8163b0f4: hook_file_open (STB_LOCAL)
ffffffff81e89c7e-ffffffff81e89cba: hook_file_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hook_file_open(const struct file * file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1206
Inline: False
```
**Symbols:**

```
ffffffff816f2600-ffffffff816f28d6: hook_file_open (STB_LOCAL)
ffffffff82075105-ffffffff8207514b: hook_file_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hook_file_open(const struct file * file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1206
Inline: False
```
**Symbols:**

```
ffffffff8172ca40-ffffffff8172cd40: hook_file_open (STB_LOCAL)
ffffffff820f4cc3-ffffffff820f4d0d: hook_file_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hook_file_open(const struct file * file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176d650)
Location: security/landlock/fs.c:1122
Inline: False
```
**Symbols:**

```
ffffffff8176d650-ffffffff8176d8ca: hook_file_open (STB_LOCAL)
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
