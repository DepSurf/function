# Function: <code>ZSTD_initDDict_internal</code>

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
size_t ZSTD_initDDict_internal(ZSTD_DDict *ddict, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_ddict.c (ffffffff817504c0)
Location: lib/zstd/decompress/zstd_ddict.c:117
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initStaticDDict
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced
```
**Symbols:**

```
ffffffff817504c0-ffffffff8175064a: ZSTD_initDDict_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_initDDict_internal(ZSTD_DDict *ddict, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_ddict.c (ffffffff81874620)
Location: lib/zstd/decompress/zstd_ddict.c:117
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initStaticDDict
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced
```
**Symbols:**

```
ffffffff81874620-ffffffff818747aa: ZSTD_initDDict_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_initDDict_internal(ZSTD_DDict *ddict, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_ddict.c (ffffffff818b5380)
Location: lib/zstd/decompress/zstd_ddict.c:117
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initStaticDDict
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced
```
**Symbols:**

```
ffffffff818b5380-ffffffff818b550a: ZSTD_initDDict_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_initDDict_internal(ZSTD_DDict *ddict, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_ddict.c (ffffffff81906f40)
Location: lib/zstd/decompress/zstd_ddict.c:117
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initStaticDDict
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced
```
**Symbols:**

```
ffffffff81906f40-ffffffff819070ca: ZSTD_initDDict_internal (STB_LOCAL)
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
