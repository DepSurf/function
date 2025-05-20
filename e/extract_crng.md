# Function: <code>extract_crng</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81566570)
Location: drivers/char/random.c:887
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff81566570-ffffffff815665b1: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81592cd0)
Location: drivers/char/random.c:887
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff81592cd0-ffffffff81592d11: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a7e90)
Location: drivers/char/random.c:871
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff815a7e90-ffffffff815a7ed1: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160e790)
Location: drivers/char/random.c:870
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff8160e790-ffffffff8160e7d1: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void extract_crng(__u32 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816480f0)
Location: drivers/char/random.c:979
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff816480f0-ffffffff81648131: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81666590)
Location: drivers/char/random.c:992
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff81666590-ffffffff816665d1: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169afa0)
Location: drivers/char/random.c:1069
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff8169afa0-ffffffff8169afe1: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bdcd0)
Location: drivers/char/random.c:1069
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff816bdcd0-ffffffff816bdd11: extract_crng (STB_LOCAL)
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
In drivers/char/random.c (ffffffff817725bd)
Location: drivers/char/random.c:1016
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
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
In drivers/char/random.c (ffffffff8178d62d)
Location: drivers/char/random.c:1016
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
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
In drivers/char/random.c (ffffffff817705de)
Location: drivers/char/random.c:1006
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
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
In drivers/char/random.c (ffffffff817f6076)
Location: drivers/char/random.c:1042
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
</details>
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
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108afb48)
Location: drivers/char/random.c:1069
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffff8000108afb48-ffff8000108afbc8: extract_crng (STB_LOCAL)
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
In drivers/char/random.c (c09aa7a8)
Location: drivers/char/random.c:1069
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000947d80)
Location: drivers/char/random.c:1069
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
c000000000947d80-c000000000947df0: extract_crng (STB_LOCAL)
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
In drivers/char/random.c (ffffffe000562486)
Location: drivers/char/random.c:1069
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
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
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81683740)
Location: drivers/char/random.c:1069
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff81683740-ffffffff81683781: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816613c0)
Location: drivers/char/random.c:1069
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff816613c0-ffffffff81661401: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b1b10)
Location: drivers/char/random.c:1069
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff816b1b10-ffffffff816b1b51: extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void extract_crng(__u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cbfb0)
Location: drivers/char/random.c:1069
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_crng_backtrack_protect
```
**Symbols:**

```
ffffffff816cbfb0-ffffffff816cbff1: extract_crng (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__u8 *out</code> ➡️ <code>__u32 *out</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__u32 *out</code> ➡️ <code>__u8 *out</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
