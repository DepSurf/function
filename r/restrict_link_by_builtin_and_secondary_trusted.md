# Function: <code>restrict_link_by_builtin_and_secondary_trusted</code>

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
int restrict_link_by_builtin_and_secondary_trusted(struct key *keyring, const struct key_type *type, const union key_payload *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8119f110)
Location: certs/system_keyring.c:67
Inline: False
```
**Symbols:**

```
ffffffff8119f110-ffffffff8119f14e: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *keyring, const struct key_type *type, const union key_payload *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811aebc0)
Location: certs/system_keyring.c:67
Inline: False
```
**Symbols:**

```
ffffffff811aebc0-ffffffff811aebfe: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811b54e0)
Location: certs/system_keyring.c:55
Inline: False
```
**Symbols:**

```
ffffffff811b54e0-ffffffff811b551c: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811c95d0)
Location: certs/system_keyring.c:55
Inline: False
```
**Symbols:**

```
ffffffff811c95d0-ffffffff811c960c: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811ea720)
Location: certs/system_keyring.c:56
Inline: False
```
**Symbols:**

```
ffffffff811ea720-ffffffff811ea75a: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811fb290)
Location: certs/system_keyring.c:56
Inline: False
```
**Symbols:**

```
ffffffff811fb290-ffffffff811fb2ca: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81212970)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffffffff81212970-ffffffff812129aa: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81220150)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffffffff81220150-ffffffff8122018a: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8124d560)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffffffff8124d560-ffffffff8124d59a: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff812579d0)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffffffff812579d0-ffffffff81257a0a: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8125be30)
Location: certs/system_keyring.c:57
Inline: False
```
**Symbols:**

```
ffffffff8125be30-ffffffff8125be6a: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81297ce0)
Location: certs/system_keyring.c:57
Inline: False
```
**Symbols:**

```
ffffffff81297ce0-ffffffff81297d1a: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff812ee039)
Location: certs/system_keyring.c:59
Inline: True
Inline callers:
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
```
**Symbols:**

```
ffffffff812ee090-ffffffff812ee0e2: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81358479)
Location: certs/system_keyring.c:59
Inline: True
Inline callers:
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
```
**Symbols:**

```
ffffffff813584f0-ffffffff81358542: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81389d09)
Location: certs/system_keyring.c:67
Inline: True
Inline callers:
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
```
**Symbols:**

```
ffffffff81389d80-ffffffff81389dd2: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff813b3789)
Location: certs/system_keyring.c:87
Inline: True
Inline callers:
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
```
**Symbols:**

```
ffffffff813b3840-ffffffff813b3892: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
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
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffff8000102ad2f8)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffff8000102ad2f8-ffff8000102ad378: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (c04d9cfc)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
c04d9cfc-c04d9d54: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (c000000000360f40)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
c000000000360f40-c000000000360fc0: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffe0001d37da)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffffffe0001d37da-ffffffe0001d3840: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
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
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff812187a0)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffffffff812187a0-ffffffff812187da: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8120b9b0)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffffffff8120b9b0-ffffffff8120b9ea: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81216540)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffffffff81216540-ffffffff8121657a: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int restrict_link_by_builtin_and_secondary_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restrict_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff812255c0)
Location: certs/system_keyring.c:54
Inline: False
```
**Symbols:**

```
ffffffff812255c0-ffffffff812255fa: restrict_link_by_builtin_and_secondary_trusted (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct key *dest_keyring</code>
</li>
<li>
<b>Param added. </b>
<code>struct key *restrict_key</code>
</li>
<li>
<b>Param removed. </b>
<code>struct key *keyring</code>
</li>
</ul>
</details>
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
