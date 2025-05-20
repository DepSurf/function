# Function: <code>asn1_encode_oid</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned char *asn1_encode_oid(unsigned char *data, const unsigned char *end_data, u32 *oid, int oid_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_encoder.c (ffffffff815ec130)
Location: lib/asn1_encoder.c:141
Inline: False
```
**Symbols:**

```
ffffffff815ec130-ffffffff815ec25f: asn1_encode_oid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned char *asn1_encode_oid(unsigned char *data, const unsigned char *end_data, u32 *oid, int oid_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_encoder.c (0)
Location: lib/asn1_encoder.c:141
Inline: False
```
**Symbols:**

```
ffffffff81cde62e-ffffffff81cde69d: asn1_encode_oid.cold (STB_LOCAL)
ffffffff81658bf0-ffffffff81658d60: asn1_encode_oid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned char *asn1_encode_oid(unsigned char *data, const unsigned char *end_data, u32 *oid, int oid_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_encoder.c (0)
Location: lib/asn1_encoder.c:141
Inline: False
```
**Symbols:**

```
ffffffff81ea4a52-ffffffff81ea4abe: asn1_encode_oid.cold (STB_LOCAL)
ffffffff81771020-ffffffff81771198: asn1_encode_oid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned char *asn1_encode_oid(unsigned char *data, const unsigned char *end_data, u32 *oid, int oid_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_encoder.c (0)
Location: lib/asn1_encoder.c:141
Inline: False
```
**Symbols:**

```
ffffffff8208d568-ffffffff8208d5d4: asn1_encode_oid.cold (STB_LOCAL)
ffffffff818a0c10-ffffffff818a0d88: asn1_encode_oid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned char *asn1_encode_oid(unsigned char *data, const unsigned char *end_data, u32 *oid, int oid_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_encoder.c (0)
Location: lib/asn1_encoder.c:141
Inline: False
```
**Symbols:**

```
ffffffff8210d906-ffffffff8210d972: asn1_encode_oid.cold (STB_LOCAL)
ffffffff818e3180-ffffffff818e3300: asn1_encode_oid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned char *asn1_encode_oid(unsigned char *data, const unsigned char *end_data, u32 *oid, int oid_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_encoder.c (0)
Location: lib/asn1_encoder.c:141
Inline: False
```
**Symbols:**

```
ffffffff821eb543-ffffffff821eb5af: asn1_encode_oid.cold (STB_LOCAL)
ffffffff8192a110-ffffffff8192a290: asn1_encode_oid (STB_GLOBAL)
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
