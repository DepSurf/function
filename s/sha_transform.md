# Function: <code>sha_transform</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff813f0560)
Location: lib/sha1.c:81
Inline: False
Direct callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff813f0560-ffffffff813f1622: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff81436f10)
Location: lib/sha1.c:81
Inline: False
Direct callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff81436f10-ffffffff81437fb2: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff81453f00)
Location: lib/sha1.c:81
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff81453f00-ffffffff81454fa2: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff818f4030)
Location: lib/sha1.c:81
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff818f4030-ffffffff818f50d2: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff8197aa30)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff8197aa30-ffffffff8197bad2: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff819d6fb0)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff819d6fb0-ffffffff819d805a: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff81a0f1f0)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff81a0f1f0-ffffffff81a1029a: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff81a7e760)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff81a7e760-ffffffff81a7f824: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff81ab5960)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff81ab5960-ffffffff81ab6a24: sha_transform (STB_GLOBAL)
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
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffff800010d901b0)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffff800010d901b0-ffff800010d9120c: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (c0e8a968)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
c0e8a968-c0e8bd4c: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (c000000000ed34f0)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
c000000000ed34f0-c000000000ed46fc: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffe0008b83de)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffe0008b83de-ffffffe0008ba048: sha_transform (STB_GLOBAL)
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
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff81a547b0)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff81a547b0-ffffffff81a55874: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff81a11890)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff81a11890-ffffffff81a12954: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff81ac0ba0)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff81ac0ba0-ffffffff81ac1c64: sha_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sha_transform(__u32 *digest, const char *data, __u32 *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sha1.c (ffffffff81acd070)
Location: lib/sha1.c:82
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - drivers/char/random.c:extract_buf
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
```
**Symbols:**

```
ffffffff81acd070-ffffffff81ace134: sha_transform (STB_GLOBAL)
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
