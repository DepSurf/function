# Function: <code>pkcs7_free_signed_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pkcs7_free_signed_info(struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813adf60)
Location: crypto/asymmetric_keys/pkcs7_parser.c:44
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff813adf60-ffffffff813adf99: pkcs7_free_signed_info (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813f1dd9)
Location: crypto/asymmetric_keys/pkcs7_parser.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8140b649)
Location: crypto/asymmetric_keys/pkcs7_parser.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814191e3)
Location: crypto/asymmetric_keys/pkcs7_parser.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81443d13)
Location: crypto/asymmetric_keys/pkcs7_parser.c:49
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81476c82)
Location: crypto/asymmetric_keys/pkcs7_parser.c:49
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81494e22)
Location: crypto/asymmetric_keys/pkcs7_parser.c:49
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c282d)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814db65d)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8153af4d)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81557d5d)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff815606ad)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff815c1a5d)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8166be7f)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81726b0a)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81762f0a)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff817a4ab6)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffff8000105d7968)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (c0784fbc)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (c000000000766da0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffe00041b75c)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814d3c3d)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c465d)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814cfccd)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
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
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814e879d)
Location: crypto/asymmetric_keys/pkcs7_parser.c:45
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
