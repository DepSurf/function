# Function: <code>__end_buffer_read_notouch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81242650)
Location: fs/buffer.c:154
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_read_nobh
```
**Symbols:**

```
ffffffff81242650-ffffffff81242673: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126a9b0)
Location: fs/buffer.c:152
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff8126a9b0-ffffffff8126a9d3: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127dac0)
Location: fs/buffer.c:153
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff8127dac0-ffffffff8127dae3: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128b6e0)
Location: fs/buffer.c:153
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff8128b6e0-ffffffff8128b703: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ae260)
Location: fs/buffer.c:153
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff812ae260-ffffffff812ae283: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d6080)
Location: fs/buffer.c:146
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff812d6080-ffffffff812d60aa: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812eb450)
Location: fs/buffer.c:146
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff812eb450-ffffffff812eb47a: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130cb00)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff8130cb00-ffffffff8130cb31: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131fb10)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff8131fb10-ffffffff8131fb41: __end_buffer_read_notouch (STB_LOCAL)
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
In fs/buffer.c (ffffffff8135a4e5)
Location: fs/buffer.c:142
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
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
In fs/buffer.c (ffffffff81368545)
Location: fs/buffer.c:142
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
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
In fs/buffer.c (ffffffff8136f175)
Location: fs/buffer.c:142
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
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
In fs/buffer.c (ffffffff813bde15)
Location: fs/buffer.c:142
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
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
In fs/buffer.c (ffffffff81444175)
Location: fs/buffer.c:142
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
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
In fs/buffer.c (ffffffff814d32d5)
Location: fs/buffer.c:142
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_sync
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
In fs/buffer.c (ffffffff8150a3e5)
Location: fs/buffer.c:142
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_sync
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
In fs/buffer.c (ffffffff8153f3d5)
Location: fs/buffer.c:143
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_sync
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
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d8cd0)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffff8000103d8cd0-ffff8000103d8d88: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b11fc)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
c05b11fc-c05b1250: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dbcc0)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
c0000000004dbcc0-c0000000004dbd28: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000290f72)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffe000290f72-ffffffe000290fc8: __end_buffer_read_notouch (STB_LOCAL)
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
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813180f0)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff813180f0-ffffffff81318121: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81308ce0)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff81308ce0-ffffffff81308d11: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81315bc0)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff81315bc0-ffffffff81315bf1: __end_buffer_read_notouch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __end_buffer_read_notouch(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813277c0)
Location: fs/buffer.c:147
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_sync
```
**Symbols:**

```
ffffffff813277c0-ffffffff813277f1: __end_buffer_read_notouch (STB_LOCAL)
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
