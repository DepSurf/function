# Function: <code>asn1_find_indefinite_length</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff8141a929)
Location: lib/asn1_decoder.c:60
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff81462b60)
Location: lib/asn1_decoder.c:61
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff81481690)
Location: lib/asn1_decoder.c:61
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (ffffffff8148a75d)
Location: lib/asn1_decoder.c:61
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (ffffffff814c6845)
Location: lib/asn1_decoder.c:61
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:61
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:61
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int asn1_find_indefinite_length(const unsigned char *data, size_t datalen, size_t *_dp, size_t *_len, const char **_errmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff815e4230)
Location: lib/asn1_decoder.c:57
Inline: False
Direct callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
```
**Symbols:**

```
ffffffff815e4230-ffffffff815e43b7: asn1_find_indefinite_length (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int asn1_find_indefinite_length(const unsigned char *data, size_t datalen, size_t *_dp, size_t *_len, const char **_errmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff81608760)
Location: lib/asn1_decoder.c:57
Inline: False
Direct callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
```
**Symbols:**

```
ffffffff81608760-ffffffff816088e7: asn1_find_indefinite_length (STB_LOCAL)
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (ffffffe00049328e)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
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
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:57
Inline: True
Inline callers:
  - lib/asn1_decoder.c:asn1_ber_decoder
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
