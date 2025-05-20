# Function: <code>verify_header</code>

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
In security/apparmor/policy_unpack.c (ffffffff8138287c)
Location: security/apparmor/policy_unpack.c:721
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff813bcac1)
Location: security/apparmor/policy_unpack.c:800
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff813d3ef1)
Location: security/apparmor/policy_unpack.c:800
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff813e6cb1)
Location: security/apparmor/policy_unpack.c:885
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff8140deb1)
Location: security/apparmor/policy_unpack.c:885
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff8143fb5a)
Location: security/apparmor/policy_unpack.c:932
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff8145ca4c)
Location: security/apparmor/policy_unpack.c:900
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff81489ff9)
Location: security/apparmor/policy_unpack.c:922
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff814a3eb9)
Location: security/apparmor/policy_unpack.c:926
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int verify_header(struct aa_ext *e, int required, const char **ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff814fd930)
Location: security/apparmor/policy_unpack.c:996
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff814fd930-ffffffff814fdaee: verify_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int verify_header(struct aa_ext *e, int required, const char **ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8151ab90)
Location: security/apparmor/policy_unpack.c:996
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8151ab90-ffffffff8151ad4e: verify_header (STB_LOCAL)
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
In security/apparmor/policy_unpack.c (ffffffff81522694)
Location: security/apparmor/policy_unpack.c:996
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff815808e4)
Location: security/apparmor/policy_unpack.c:996
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff8161fac4)
Location: security/apparmor/policy_unpack.c:1149
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff816d2f0c)
Location: security/apparmor/policy_unpack.c:1140
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff8170bf0c)
Location: security/apparmor/policy_unpack.c:1167
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff81749c1c)
Location: security/apparmor/policy_unpack.c:1201
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (0)
Location: security/apparmor/policy_unpack.c:926
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (c074add8)
Location: security/apparmor/policy_unpack.c:926
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (c000000000710f20)
Location: security/apparmor/policy_unpack.c:926
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffe0003e62d8)
Location: security/apparmor/policy_unpack.c:926
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff8149c499)
Location: security/apparmor/policy_unpack.c:926
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff8148ceb9)
Location: security/apparmor/policy_unpack.c:926
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff81498539)
Location: security/apparmor/policy_unpack.c:926
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
In security/apparmor/policy_unpack.c (ffffffff814b0689)
Location: security/apparmor/policy_unpack.c:926
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
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
