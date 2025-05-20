# Function: <code>seq_buf_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *seq_buf_alloc(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81230750)
Location: fs/seq_file.c:26
Inline: False
Direct callers:
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:single_open_size
```
**Symbols:**

```
ffffffff81230750-ffffffff8123078d: seq_buf_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *seq_buf_alloc(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81258de0)
Location: fs/seq_file.c:26
Inline: False
Direct callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
```
**Symbols:**

```
ffffffff81258de0-ffffffff81258e1d: seq_buf_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *seq_buf_alloc(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126c290)
Location: fs/seq_file.c:26
Inline: False
Direct callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
```
**Symbols:**

```
ffffffff8126c290-ffffffff8126c2cd: seq_buf_alloc (STB_LOCAL)
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
In fs/seq_file.c (ffffffff8127a9ab)
Location: fs/seq_file.c:26
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
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
In fs/seq_file.c (ffffffff8129d41b)
Location: fs/seq_file.c:27
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
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
In fs/seq_file.c (ffffffff812c3085)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
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
In fs/seq_file.c (ffffffff812d7ff5)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (ffffffff812f6505)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (ffffffff813080d5)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (ffffffff813414b5)
Location: fs/seq_file.c:32
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (ffffffff8134d525)
Location: fs/seq_file.c:33
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
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
In fs/seq_file.c (ffffffff813546c5)
Location: fs/seq_file.c:33
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
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
In fs/seq_file.c (ffffffff813a2aa5)
Location: fs/seq_file.c:33
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
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
In fs/seq_file.c (ffffffff814267f5)
Location: fs/seq_file.c:33
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
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
In fs/seq_file.c (ffffffff814b3065)
Location: fs/seq_file.c:33
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
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
In fs/seq_file.c (ffffffff814e80b5)
Location: fs/seq_file.c:33
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
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
In fs/seq_file.c (ffffffff8151bf45)
Location: fs/seq_file.c:33
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
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
In fs/seq_file.c (ffff8000103bbc84)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (c05993d4)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (c0000000004b91d0)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (ffffffe00027d6dc)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (ffffffff813006b5)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (ffffffff812f12d5)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (ffffffff812fe4a5)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
In fs/seq_file.c (ffffffff8130f7e5)
Location: fs/seq_file.c:30
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
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
</ul>
