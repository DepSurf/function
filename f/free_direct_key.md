# Function: <code>free_direct_key</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8134e722)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff8134e250-ffffffff8134e277: free_direct_key.part.0 (STB_LOCAL)
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
In fs/crypto/keysetup_v1.c (ffffffff8139457e)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
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
In fs/crypto/keysetup_v1.c (ffffffff813a5a57)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
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
In fs/crypto/keysetup_v1.c (ffffffff813acab7)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
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
In fs/crypto/keysetup_v1.c (ffffffff813fc427)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
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
In fs/crypto/keysetup_v1.c (ffffffff8146f8c1)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
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
In fs/crypto/keysetup_v1.c (ffffffff81501076)
Location: fs/crypto/keysetup_v1.c:155
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
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
In fs/crypto/keysetup_v1.c (ffffffff81538706)
Location: fs/crypto/keysetup_v1.c:155
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
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
In fs/crypto/keysetup_v1.c (ffffffff8156d885)
Location: fs/crypto/keysetup_v1.c:155
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffff80001040fadc)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffff80001040f548-ffff80001040f580: free_direct_key.part.0 (STB_LOCAL)
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
In fs/crypto/keysetup_v1.c (c05dc52c)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
c05dbff8-c05dc028: free_direct_key.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (c00000000051d57c)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
c00000000051cd80-c00000000051cdd4: free_direct_key.part.0 (STB_LOCAL)
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
In fs/crypto/keysetup_v1.c (ffffffe0002b86d0)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffe0002b8128-ffffffe0002b8160: free_direct_key.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81346d02)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff81346830-ffffffff81346857: free_direct_key.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813379e2)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff81337510-ffffffff81337537: free_direct_key.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813447d2)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff81344300-ffffffff81344327: free_direct_key.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81357ab2)
Location: fs/crypto/keysetup_v1.c:154
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff813575e0-ffffffff81357607: free_direct_key.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
