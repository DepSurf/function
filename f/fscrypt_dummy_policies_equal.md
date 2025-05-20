# Function: <code>fscrypt_dummy_policies_equal</code>

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
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fscrypt_dummy_policies_equal(const struct fscrypt_dummy_policy *p1, const struct fscrypt_dummy_policy *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81470070)
Location: fs/crypto/policy.c:794
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
```
**Symbols:**

```
ffffffff81470070-ffffffff814700e1: fscrypt_dummy_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fscrypt_dummy_policies_equal(const struct fscrypt_dummy_policy *p1, const struct fscrypt_dummy_policy *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81501a90)
Location: fs/crypto/policy.c:833
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
```
**Symbols:**

```
ffffffff81501a90-ffffffff81501b01: fscrypt_dummy_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fscrypt_dummy_policies_equal(const struct fscrypt_dummy_policy *p1, const struct fscrypt_dummy_policy *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff815392c0)
Location: fs/crypto/policy.c:832
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
```
**Symbols:**

```
ffffffff815392c0-ffffffff81539302: fscrypt_dummy_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fscrypt_dummy_policies_equal(const struct fscrypt_dummy_policy *p1, const struct fscrypt_dummy_policy *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8156e4b0)
Location: fs/crypto/policy.c:859
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_check_opt_consistency
  - fs/ext4/super.c:ext4_check_opt_consistency
```
**Symbols:**

```
ffffffff8156e4b0-ffffffff8156e4f2: fscrypt_dummy_policies_equal (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
