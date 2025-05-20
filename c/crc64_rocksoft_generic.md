# Function: <code>crc64_rocksoft_generic</code>

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
u64 crc64_rocksoft_generic(u64 crc, const void *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64.c (ffffffff816fa020)
Location: lib/crc64.c:73
Inline: False
Direct callers:
  - crypto/crc64_rocksoft_generic.c:chksum_digest
  - crypto/crc64_rocksoft_generic.c:chksum_finup
  - crypto/crc64_rocksoft_generic.c:chksum_update
  - lib/crc64-rocksoft.c:crc64_rocksoft_update
```
**Symbols:**

```
ffffffff816fa020-ffffffff816fa06f: crc64_rocksoft_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 crc64_rocksoft_generic(u64 crc, const void *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64.c (ffffffff817eca10)
Location: lib/crc64.c:73
Inline: False
Direct callers:
  - crypto/crc64_rocksoft_generic.c:chksum_digest
  - crypto/crc64_rocksoft_generic.c:chksum_finup
  - crypto/crc64_rocksoft_generic.c:chksum_update
  - lib/crc64-rocksoft.c:crc64_rocksoft_update
```
**Symbols:**

```
ffffffff817eca10-ffffffff817eca5f: crc64_rocksoft_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 crc64_rocksoft_generic(u64 crc, const void *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64.c (ffffffff8182cbf0)
Location: lib/crc64.c:73
Inline: False
Direct callers:
  - crypto/crc64_rocksoft_generic.c:chksum_digest
  - crypto/crc64_rocksoft_generic.c:chksum_finup
  - crypto/crc64_rocksoft_generic.c:chksum_update
  - lib/crc64-rocksoft.c:crc64_rocksoft
```
**Symbols:**

```
ffffffff8182cbf0-ffffffff8182cc3f: crc64_rocksoft_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 crc64_rocksoft_generic(u64 crc, const void *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64.c (ffffffff8187e780)
Location: lib/crc64.c:73
Inline: False
Direct callers:
  - crypto/crc64_rocksoft_generic.c:chksum_digest
  - crypto/crc64_rocksoft_generic.c:chksum_finup
  - crypto/crc64_rocksoft_generic.c:chksum_update
  - lib/crc64-rocksoft.c:crc64_rocksoft
```
**Symbols:**

```
ffffffff8187e780-ffffffff8187e7cf: crc64_rocksoft_generic (STB_GLOBAL)
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
