# Function: <code>md5_transform</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/md5.c (ffffffff813ed2a0)
Location: lib/md5.c:13
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
  - drivers/char/random.c:get_random_int
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
```
**Symbols:**

```
ffffffff813ed2a0-ffffffff813eda53: md5_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/md5.c (ffffffff814335c0)
Location: lib/md5.c:13
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:get_random_int
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
```
**Symbols:**

```
ffffffff814335c0-ffffffff81433d10: md5_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/md5.c (ffffffff8144f830)
Location: lib/md5.c:13
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:get_random_int
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
```
**Symbols:**

```
ffffffff8144f830-ffffffff8144ff80: md5_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff81408600)
Location: crypto/md5.c:60
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff81408600-ffffffff81408d6d: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff81431020)
Location: crypto/md5.c:60
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff81431020-ffffffff8143178d: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff81463b80)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff81463b80-ffffffff814642f9: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff814817f0)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff814817f0-ffffffff81481f69: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff814afa20)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff814afa20-ffffffff814b0199: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff814ca690)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff814ca690-ffffffff814cae09: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff81529aa0)
Location: crypto/md5.c:40
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff81529aa0-ffffffff8152a1a3: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff81546a50)
Location: crypto/md5.c:40
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff81546a50-ffffffff81547153: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff8154f110)
Location: crypto/md5.c:40
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff8154f110-ffffffff8154f812: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff815afa60)
Location: crypto/md5.c:40
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff815afa60-ffffffff815b0162: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff816582f0)
Location: crypto/md5.c:40
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff816582f0-ffffffff81658a10: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff817126f0)
Location: crypto/md5.c:40
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff817126f0-ffffffff81712e10: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff8174d390)
Location: crypto/md5.c:40
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff8174d390-ffffffff8174dab0: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff8178efe0)
Location: crypto/md5.c:40
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff8178efe0-ffffffff8178f700: md5_transform (STB_LOCAL)
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
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffff8000105c64c0)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffff8000105c64c0-ffff8000105c6ebc: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (c0773140)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
c0773140-c0773b7c: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (c000000000750050)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
c000000000750050-c0000000007509dc: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffe00040a4bc)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffe00040a4bc-ffffffe00040b064: md5_transform (STB_LOCAL)
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
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff814c2c70)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff814c2c70-ffffffff814c33e9: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff814b3690)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff814b3690-ffffffff814b3e09: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff814bed00)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff814bed00-ffffffff814bf479: md5_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void md5_transform(__u32 *hash, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/md5.c (ffffffff814d77d0)
Location: crypto/md5.c:43
Inline: False
Direct callers:
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_final
  - crypto/md5.c:md5_update
  - crypto/md5.c:md5_update
```
**Symbols:**

```
ffffffff814d77d0-ffffffff814d7f49: md5_transform (STB_LOCAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
