# Function: <code>key_or_keyring_common</code>

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
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81417590)
Location: crypto/asymmetric_keys/restrict.c:119
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff81417590-ffffffff81417734: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81441fd0)
Location: crypto/asymmetric_keys/restrict.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff81441fd0-ffffffff8144218a: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81474e90)
Location: crypto/asymmetric_keys/restrict.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff81474e90-ffffffff81475069: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81492ad0)
Location: crypto/asymmetric_keys/restrict.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff81492ad0-ffffffff81492ca9: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814c01c0)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff814c01c0-ffffffff814c0393: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814d9010)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff814d9010-ffffffff814d91e3: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff815388b0)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff815388b0-ffffffff81538ab1: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff815556b0)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff815556b0-ffffffff815558b1: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff8155de30)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff8155de30-ffffffff8155e02e: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff815bf140)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff815bf140-ffffffff815bf33e: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81668f20)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff81668f20-ffffffff81669180: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81723770)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff81723770-ffffffff817239d0: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff8175fa70)
Location: crypto/asymmetric_keys/restrict.c:158
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff8175fa70-ffffffff8175fcd0: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff817a1300)
Location: crypto/asymmetric_keys/restrict.c:206
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff817a1300-ffffffff817a1560: key_or_keyring_common (STB_LOCAL)
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
In crypto/asymmetric_keys/restrict.c (ffff8000105d5048)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: True
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffff8000105d5048-ffff8000105d5254: key_or_keyring_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (c07829d4)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
c07829d4-c0782ba4: key_or_keyring_common (STB_LOCAL)
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
In crypto/asymmetric_keys/restrict.c (c000000000763280)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: True
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
c000000000763280-c0000000007635e0: key_or_keyring_common.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/restrict.c (ffffffe000419388)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: True
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffe000419388-ffffffe0004194fe: key_or_keyring_common.isra.0 (STB_LOCAL)
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
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814d15f0)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff814d15f0-ffffffff814d17c3: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814c2010)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff814c2010-ffffffff814c21e3: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814cd680)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff814cd680-ffffffff814cd853: key_or_keyring_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int key_or_keyring_common(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trusted, bool check_dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814e6150)
Location: crypto/asymmetric_keys/restrict.c:118
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring_chain
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_key_or_keyring
```
**Symbols:**

```
ffffffff814e6150-ffffffff814e6323: key_or_keyring_common (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
