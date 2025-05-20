# Function: <code>file_free_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8120e310)
Location: fs/file_table.c:44
Inline: False
```
**Symbols:**

```
ffffffff8120e310-ffffffff8120e342: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81234d40)
Location: fs/file_table.c:44
Inline: False
```
**Symbols:**

```
ffffffff81234d40-ffffffff81234d70: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812478f0)
Location: fs/file_table.c:44
Inline: False
```
**Symbols:**

```
ffffffff812478f0-ffffffff81247920: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81253030)
Location: fs/file_table.c:45
Inline: False
```
**Symbols:**

```
ffffffff81253030-ffffffff81253067: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81275130)
Location: fs/file_table.c:45
Inline: False
```
**Symbols:**

```
ffffffff81275130-ffffffff81275167: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8129b9c0)
Location: fs/file_table.c:44
Inline: False
```
**Symbols:**

```
ffffffff8129b9c0-ffffffff8129b9f2: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812b0740)
Location: fs/file_table.c:44
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff812b0740-ffffffff812b078a: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812cd080)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff812cd080-ffffffff812cd0ca: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812deaa0)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff812deaa0-ffffffff812deaea: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813158f0)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff813158f0-ffffffff8131593a: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81320e50)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff81320e50-ffffffff81320e9a: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81326f50)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff81326f50-ffffffff81326f9a: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81374510)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff81374510-ffffffff8137455a: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813f34f0)
Location: fs/file_table.c:46
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff813f34f0-ffffffff813f354a: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8147c290)
Location: fs/file_table.c:46
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff8147c290-ffffffff8147c2ea: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff814b1440)
Location: fs/file_table.c:64
Inline: False
```
**Symbols:**

```
ffffffff814b1440-ffffffff814b149f: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffff800010385190)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffff800010385190-ffff800010385214: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c056e078)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
c056e078-c056e0e4: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c00000000047b100)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
c00000000047b100-c00000000047b1a0: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffe000257fbc)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffe000257fbc-ffffffe00025800a: file_free_rcu (STB_LOCAL)
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
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d7080)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff812d7080-ffffffff812d70ca: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812c7d00)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff812c7d00-ffffffff812c7d4a: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d4e90)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff812d4e90-ffffffff812d4eda: file_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void file_free_rcu(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812e5cf0)
Location: fs/file_table.c:45
Inline: False
Direct callers:
  - fs/file_table.c:__alloc_file
```
**Symbols:**

```
ffffffff812e5cf0-ffffffff812e5d3a: file_free_rcu (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
