# Function: <code>crng_backtrack_protect</code>

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
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81567930)
Location: drivers/char/random.c:924
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81567930-ffffffff81567976: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81594060)
Location: drivers/char/random.c:924
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81594060-ffffffff815940a6: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a7f60)
Location: drivers/char/random.c:908
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff815a7f60-ffffffff815a7fa6: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160e860)
Location: drivers/char/random.c:907
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff8160e860-ffffffff8160e8a6: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void crng_backtrack_protect(__u32 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816481b0)
Location: drivers/char/random.c:1016
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff816481b0-ffffffff816481f6: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81666650)
Location: drivers/char/random.c:1029
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff81666650-ffffffff81666696: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169c390)
Location: drivers/char/random.c:1106
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff8169c390-ffffffff8169c3d6: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bf100)
Location: drivers/char/random.c:1106
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff816bf100-ffffffff816bf146: crng_backtrack_protect (STB_LOCAL)
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
In drivers/char/random.c (ffffffff817734ad)
Location: drivers/char/random.c:1053
Inline: True
Inline callers:
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
In drivers/char/random.c (ffffffff8178e47d)
Location: drivers/char/random.c:1053
Inline: True
Inline callers:
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
In drivers/char/random.c (ffffffff81770ced)
Location: drivers/char/random.c:1043
Inline: True
Inline callers:
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
In drivers/char/random.c (ffffffff817f67fc)
Location: drivers/char/random.c:1071
Inline: True
Inline callers:
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
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108afcc8)
Location: drivers/char/random.c:1106
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffff8000108afcc8-ffff8000108afd54: crng_backtrack_protect (STB_LOCAL)
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
In drivers/char/random.c (c09aa578)
Location: drivers/char/random.c:1106
Inline: True
Inline callers:
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
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000947ec0)
Location: drivers/char/random.c:1106
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
c000000000947ec0-c000000000947f34: crng_backtrack_protect (STB_LOCAL)
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
In drivers/char/random.c (ffffffe00056228c)
Location: drivers/char/random.c:1106
Inline: True
Inline callers:
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
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81684b50)
Location: drivers/char/random.c:1106
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff81684b50-ffffffff81684b96: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816627f0)
Location: drivers/char/random.c:1106
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff816627f0-ffffffff81662836: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b2f40)
Location: drivers/char/random.c:1106
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff816b2f40-ffffffff816b2f86: crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cd4a0)
Location: drivers/char/random.c:1106
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff816cd4a0-ffffffff816cd4e6: crng_backtrack_protect (STB_LOCAL)
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
<code>__u8 *tmp</code> ➡️ <code>__u32 *tmp</code>
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
<code>__u32 *tmp</code> ➡️ <code>__u8 *tmp</code>
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
