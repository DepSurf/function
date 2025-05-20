# Function: <code>_extract_crng</code>

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
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815664c0)
Location: drivers/char/random.c:870
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff815664c0-ffffffff8156656c: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81592c20)
Location: drivers/char/random.c:870
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81592c20-ffffffff81592ccc: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a7de0)
Location: drivers/char/random.c:854
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff815a7de0-ffffffff815a7e8c: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160e6e0)
Location: drivers/char/random.c:853
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff8160e6e0-ffffffff8160e78c: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u32 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81648030)
Location: drivers/char/random.c:961
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81648030-ffffffff816480e9: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816664d0)
Location: drivers/char/random.c:974
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816664d0-ffffffff8166658e: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169aee0)
Location: drivers/char/random.c:1051
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff8169aee0-ffffffff8169af9e: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bdc10)
Location: drivers/char/random.c:1051
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816bdc10-ffffffff816bdcce: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81772490)
Location: drivers/char/random.c:998
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81772490-ffffffff8177254e: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178d500)
Location: drivers/char/random.c:998
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff8178d500-ffffffff8178d5be: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817704b0)
Location: drivers/char/random.c:988
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff817704b0-ffffffff8177056e: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f5e60)
Location: drivers/char/random.c:1021
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff817f5e60-ffffffff817f5f21: _extract_crng (STB_LOCAL)
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
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108afa18)
Location: drivers/char/random.c:1051
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffff8000108afa18-ffff8000108afb44: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (c09aa2ac)
Location: drivers/char/random.c:1051
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
c09aa2ac-c09aa364: _extract_crng.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000947c60)
Location: drivers/char/random.c:1051
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
c000000000947c60-c000000000947d80: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffe000562086)
Location: drivers/char/random.c:1051
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffe000562086-ffffffe000562148: _extract_crng.constprop.0 (STB_LOCAL)
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
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81683680)
Location: drivers/char/random.c:1051
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81683680-ffffffff8168373e: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81661300)
Location: drivers/char/random.c:1051
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81661300-ffffffff816613be: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b1a50)
Location: drivers/char/random.c:1051
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816b1a50-ffffffff816b1b0e: _extract_crng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _extract_crng(struct crng_state *crng, __u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cbef0)
Location: drivers/char/random.c:1051
Inline: False
Direct callers:
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816cbef0-ffffffff816cbfae: _extract_crng (STB_LOCAL)
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
