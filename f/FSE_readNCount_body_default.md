# Function: <code>FSE_readNCount_body_default</code>

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
size_t FSE_readNCount_body_default(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff81709940)
Location: lib/zstd/common/entropy_common.c:207
Inline: False
Direct callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
**Symbols:**

```
ffffffff81709940-ffffffff81709c6e: FSE_readNCount_body_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t FSE_readNCount_body_default(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff81884420)
Location: lib/zstd/common/entropy_common.c:207
Inline: False
Direct callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
**Symbols:**

```
ffffffff81884420-ffffffff8188474e: FSE_readNCount_body_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t FSE_readNCount_body_default(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff818c6930)
Location: lib/zstd/common/entropy_common.c:207
Inline: False
Direct callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
**Symbols:**

```
ffffffff818c6930-ffffffff818c6c5e: FSE_readNCount_body_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t FSE_readNCount_body_default(short int *normalizedCounter, unsigned int *maxSVPtr, unsigned int *tableLogPtr, const void *headerBuffer, size_t hbSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff819184f0)
Location: lib/zstd/common/entropy_common.c:207
Inline: False
Direct callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
**Symbols:**

```
ffffffff819184f0-ffffffff8191881e: FSE_readNCount_body_default (STB_LOCAL)
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
