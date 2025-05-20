# Function: <code>hook_move_mount</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int hook_move_mount(const const struct path * from_path, const const struct path * to_path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff815385f0)
Location: security/landlock/fs.c:475
Inline: True
```
**Symbols:**

```
ffffffff815385f0-ffffffff8153861f: hook_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int hook_move_mount(const const struct path * from_path, const const struct path * to_path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81596de0)
Location: security/landlock/fs.c:475
Inline: True
```
**Symbols:**

```
ffffffff81596de0-ffffffff81596e0f: hook_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int hook_move_mount(const const struct path * from_path, const const struct path * to_path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81639250)
Location: security/landlock/fs.c:1043
Inline: True
```
**Symbols:**

```
ffffffff81639250-ffffffff81639285: hook_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int hook_move_mount(const const struct path * from_path, const const struct path * to_path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff816f07f0)
Location: security/landlock/fs.c:1058
Inline: True
```
**Symbols:**

```
ffffffff816f07f0-ffffffff816f0825: hook_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int hook_move_mount(const const struct path * from_path, const const struct path * to_path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8172ac90)
Location: security/landlock/fs.c:1058
Inline: True
```
**Symbols:**

```
ffffffff8172ac90-ffffffff8172acc5: hook_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int hook_move_mount(const const struct path * from_path, const const struct path * to_path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176c780)
Location: security/landlock/fs.c:975
Inline: True
```
**Symbols:**

```
ffffffff8176c780-ffffffff8176c799: hook_move_mount (STB_LOCAL)
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
