# Function: <code>ext4_resetent</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_resetent(handle_t *handle, struct ext4_renament *ent, unsigned int ino, unsigned int file_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81426110)
Location: fs/ext4/namei.c:3604
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81426110-ffffffff8142623a: ext4_resetent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_resetent(handle_t *handle, struct ext4_renament *ent, unsigned int ino, unsigned int file_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142ccb0)
Location: fs/ext4/namei.c:3734
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8142ccb0-ffffffff8142cdba: ext4_resetent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_resetent(handle_t *handle, struct ext4_renament *ent, unsigned int ino, unsigned int file_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81480bc0)
Location: fs/ext4/namei.c:3564
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81480bc0-ffffffff81480cca: ext4_resetent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_resetent(handle_t *handle, struct ext4_renament *ent, unsigned int ino, unsigned int file_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81503ae0)
Location: fs/ext4/namei.c:3621
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81503ae0-ffffffff81503bf1: ext4_resetent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_resetent(handle_t *handle, struct ext4_renament *ent, unsigned int ino, unsigned int file_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159e670)
Location: fs/ext4/namei.c:3638
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8159e670-ffffffff8159e781: ext4_resetent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_resetent(handle_t *handle, struct ext4_renament *ent, unsigned int ino, unsigned int file_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d4f80)
Location: fs/ext4/namei.c:3660
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff815d4f80-ffffffff815d508d: ext4_resetent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_resetent(handle_t *handle, struct ext4_renament *ent, unsigned int ino, unsigned int file_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160d620)
Location: fs/ext4/namei.c:3668
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8160d620-ffffffff8160d72d: ext4_resetent (STB_LOCAL)
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
