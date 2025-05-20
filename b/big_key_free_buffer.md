# Function: <code>big_key_free_buffer</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff813ecb50)
Location: security/keys/big_key.c:143
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffff813ecb50-ffffffff813ecbb4: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff81407cf0)
Location: security/keys/big_key.c:143
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffff81407cf0-ffffffff81407d54: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff81434ee0)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffff81434ee0-ffffffff81434f44: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff8144ec60)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffff8144ec60-ffffffff8144ecc4: big_key_free_buffer (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffff8000105396d8)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffff8000105396d8-ffff800010539758: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (c06efdec)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
c06efdec-c06efe6c: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (c0000000006883b0)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
c0000000006883b0-c00000000068847c: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffe000397d64)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffe000397d64-ffffffe000397de2: big_key_free_buffer (STB_LOCAL)
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
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff81447240)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffff81447240-ffffffff814472a4: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff81437c90)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffff81437c90-ffffffff81437cf4: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff814432e0)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffff814432e0-ffffffff81443344: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void big_key_free_buffer(struct big_key_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff8145a610)
Location: security/keys/big_key.c:139
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffff8145a610-ffffffff8145a674: big_key_free_buffer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
