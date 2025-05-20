# Function: <code>restrict_link_by_builtin_trusted</code>

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
int restrict_link_by_builtin_trusted(struct key *keyring, const struct key_type *type, const union key_payload *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8119f2d0)
Location: certs/system_keyring.c:51
Inline: False
```
**Symbols:**

```
ffffffff8119f2d0-ffffffff8119f2e7: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *keyring, const struct key_type *type, const union key_payload *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811aed80)
Location: certs/system_keyring.c:51
Inline: False
```
**Symbols:**

```
ffffffff811aed80-ffffffff811aed97: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811b5670)
Location: certs/system_keyring.c:37
Inline: False
```
**Symbols:**

```
ffffffff811b5670-ffffffff811b5687: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811c9760)
Location: certs/system_keyring.c:37
Inline: False
```
**Symbols:**

```
ffffffff811c9760-ffffffff811c9777: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811ea890)
Location: certs/system_keyring.c:38
Inline: False
```
**Symbols:**

```
ffffffff811ea890-ffffffff811ea8a7: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811fb400)
Location: certs/system_keyring.c:38
Inline: False
```
**Symbols:**

```
ffffffff811fb400-ffffffff811fb417: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81212b00)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffffffff81212b00-ffffffff81212b17: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81220190)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffffffff81220190-ffffffff812201a7: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8124d5a0)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffffffff8124d5a0-ffffffff8124d5b7: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81257a10)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffffffff81257a10-ffffffff81257a27: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8125be70)
Location: certs/system_keyring.c:39
Inline: False
```
**Symbols:**

```
ffffffff8125be70-ffffffff8125be87: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81297d20)
Location: certs/system_keyring.c:39
Inline: False
```
**Symbols:**

```
ffffffff81297d20-ffffffff81297d37: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff812ee060)
Location: certs/system_keyring.c:41
Inline: False
```
**Symbols:**

```
ffffffff812ee060-ffffffff812ee083: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff813584b0)
Location: certs/system_keyring.c:41
Inline: False
```
**Symbols:**

```
ffffffff813584b0-ffffffff813584d3: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81389d40)
Location: certs/system_keyring.c:45
Inline: False
```
**Symbols:**

```
ffffffff81389d40-ffffffff81389d63: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff813b37c0)
Location: certs/system_keyring.c:45
Inline: False
```
**Symbols:**

```
ffffffff813b37c0-ffffffff813b37e3: restrict_link_by_builtin_trusted (STB_GLOBAL)
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
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffff8000102ad378)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffff8000102ad378-ffff8000102ad3c4: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (c04d9d54)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
c04d9d54-c04d9d7c: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (c000000000360fc0)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
c000000000360fc0-c000000000360ffc: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffe0001d3840)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffffffe0001d3840-ffffffe0001d3882: restrict_link_by_builtin_trusted (STB_GLOBAL)
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
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff812187e0)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffffffff812187e0-ffffffff812187f7: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8120b9f0)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffffffff8120b9f0-ffffffff8120ba07: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81216580)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffffffff81216580-ffffffff81216597: restrict_link_by_builtin_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int restrict_link_by_builtin_trusted(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *restriction_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81225600)
Location: certs/system_keyring.c:36
Inline: False
```
**Symbols:**

```
ffffffff81225600-ffffffff81225617: restrict_link_by_builtin_trusted (STB_GLOBAL)
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
<code>struct key *restriction_key</code>
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
