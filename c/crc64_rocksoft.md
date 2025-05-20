# Function: <code>crc64_rocksoft</code>

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
u64 crc64_rocksoft(const unsigned char *buffer, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64-rocksoft.c (ffffffff816fa110)
Location: lib/crc64-rocksoft.c:80
Inline: False
Direct callers:
  - block/t10-pi.c:ext_pi_crc64_verify
  - block/t10-pi.c:ext_pi_crc64_generate
```
**Symbols:**

```
ffffffff816fa110-ffffffff816fa12d: crc64_rocksoft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 crc64_rocksoft(const unsigned char *buffer, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64-rocksoft.c (ffffffff817ecb20)
Location: lib/crc64-rocksoft.c:80
Inline: False
Direct callers:
  - block/t10-pi.c:ext_pi_crc64_verify
  - block/t10-pi.c:ext_pi_crc64_generate
```
**Symbols:**

```
ffffffff817ecb20-ffffffff817ecb3d: crc64_rocksoft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 crc64_rocksoft(const unsigned char *buffer, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64-rocksoft.c (ffffffff8182ced0)
Location: lib/crc64-rocksoft.c:80
Inline: False
Direct callers:
  - block/t10-pi.c:ext_pi_crc64_verify
  - block/t10-pi.c:ext_pi_crc64_generate
```
**Symbols:**

```
ffffffff8182ced0-ffffffff8182cf6f: crc64_rocksoft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 crc64_rocksoft(const unsigned char *buffer, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64-rocksoft.c (ffffffff8187ea60)
Location: lib/crc64-rocksoft.c:80
Inline: False
Direct callers:
  - block/t10-pi.c:ext_pi_crc64_verify
  - block/t10-pi.c:ext_pi_crc64_generate
```
**Symbols:**

```
ffffffff8187ea60-ffffffff8187eaff: crc64_rocksoft (STB_GLOBAL)
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
