# Function: <code>asn1_encode_tag</code>

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
unsigned char *asn1_encode_tag(unsigned char *data, const unsigned char *end_data, u32 tag, const unsigned char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_encoder.c (ffffffff815ec440)
Location: lib/asn1_encoder.c:272
Inline: False
```
**Symbols:**

```
ffffffff815ec440-ffffffff815ec58a: asn1_encode_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned char *asn1_encode_tag(unsigned char *data, const unsigned char *end_data, u32 tag, const unsigned char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_encoder.c (ffffffff81658e00)
Location: lib/asn1_encoder.c:272
Inline: False
```
**Symbols:**

```
ffffffff81658e00-ffffffff81658f4a: asn1_encode_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned char *asn1_encode_tag(unsigned char *data, const unsigned char *end_data, u32 tag, const unsigned char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_encoder.c (ffffffff817711a0)
Location: lib/asn1_encoder.c:270
Inline: False
```
**Symbols:**

```
ffffffff817711a0-ffffffff817712f2: asn1_encode_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned char *asn1_encode_tag(unsigned char *data, const unsigned char *end_data, u32 tag, const unsigned char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_encoder.c (ffffffff818a0da0)
Location: lib/asn1_encoder.c:270
Inline: False
```
**Symbols:**

```
ffffffff818a0da0-ffffffff818a0ef2: asn1_encode_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned char *asn1_encode_tag(unsigned char *data, const unsigned char *end_data, u32 tag, const unsigned char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_encoder.c (ffffffff818e3310)
Location: lib/asn1_encoder.c:270
Inline: False
```
**Symbols:**

```
ffffffff818e3310-ffffffff818e3462: asn1_encode_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned char *asn1_encode_tag(unsigned char *data, const unsigned char *end_data, u32 tag, const unsigned char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_encoder.c (ffffffff8192a2a0)
Location: lib/asn1_encoder.c:270
Inline: False
```
**Symbols:**

```
ffffffff8192a2a0-ffffffff8192a3f2: asn1_encode_tag (STB_GLOBAL)
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
