# Function: <code>ext_pi_crc64_generate</code>

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
blk_status_t ext_pi_crc64_generate(struct blk_integrity_iter *iter, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff816b6760)
Location: block/t10-pi.c:288
Inline: False
Direct callers:
  - block/t10-pi.c:ext_pi_type3_generate_crc64
  - block/t10-pi.c:ext_pi_type1_generate_crc64
```
**Symbols:**

```
ffffffff816b6760-ffffffff816b6861: ext_pi_crc64_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
blk_status_t ext_pi_crc64_generate(struct blk_integrity_iter *iter, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff81776680)
Location: block/t10-pi.c:288
Inline: False
Direct callers:
  - block/t10-pi.c:ext_pi_type3_generate_crc64
  - block/t10-pi.c:ext_pi_type1_generate_crc64
```
**Symbols:**

```
ffffffff81776680-ffffffff81776781: ext_pi_crc64_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
blk_status_t ext_pi_crc64_generate(struct blk_integrity_iter *iter, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff817b6250)
Location: block/t10-pi.c:288
Inline: False
Direct callers:
  - block/t10-pi.c:ext_pi_type3_generate_crc64
  - block/t10-pi.c:ext_pi_type1_generate_crc64
```
**Symbols:**

```
ffffffff817b6250-ffffffff817b6351: ext_pi_crc64_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
blk_status_t ext_pi_crc64_generate(struct blk_integrity_iter *iter, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff817fac60)
Location: block/t10-pi.c:288
Inline: False
Direct callers:
  - block/t10-pi.c:ext_pi_type3_generate_crc64
  - block/t10-pi.c:ext_pi_type1_generate_crc64
```
**Symbols:**

```
ffffffff817fac60-ffffffff817fad61: ext_pi_crc64_generate (STB_LOCAL)
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
