# Function: <code>match_either_id</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool match_either_id(const struct asymmetric_key_ids *pair, const struct asymmetric_key_id *single);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81417550)
Location: crypto/asymmetric_keys/restrict.c:112
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
**Symbols:**

```
ffffffff81417550-ffffffff81417589: match_either_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool match_either_id(const struct asymmetric_key_ids *pair, const struct asymmetric_key_id *single);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81441f90)
Location: crypto/asymmetric_keys/restrict.c:115
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
**Symbols:**

```
ffffffff81441f90-ffffffff81441fc9: match_either_id (STB_LOCAL)
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
In crypto/asymmetric_keys/restrict.c (ffffffff81475004)
Location: crypto/asymmetric_keys/restrict.c:115
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff81492c44)
Location: crypto/asymmetric_keys/restrict.c:115
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff814c0330)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff814d9180)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff815389d6)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff815557d6)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff8155df56)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff815bf266)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff81669071)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff817238c1)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff8175fbc1)
Location: crypto/asymmetric_keys/restrict.c:151
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff817a1451)
Location: crypto/asymmetric_keys/restrict.c:199
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffff8000105d5158)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool match_either_id(const struct asymmetric_key_ids *pair, const struct asymmetric_key_id *single);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (c0782998)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
**Symbols:**

```
c0782998-c07829d4: match_either_id (STB_LOCAL)
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
In crypto/asymmetric_keys/restrict.c (c0000000007633d4)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
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
In crypto/asymmetric_keys/restrict.c (ffffffe000419446)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
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
In crypto/asymmetric_keys/restrict.c (ffffffff814d1760)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff814c2180)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff814cd7f0)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In crypto/asymmetric_keys/restrict.c (ffffffff814e62c0)
Location: crypto/asymmetric_keys/restrict.c:111
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
