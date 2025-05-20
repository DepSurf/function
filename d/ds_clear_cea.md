# Function: <code>ds_clear_cea</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100dc70)
Location: arch/x86/events/intel/ds.c:305
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100dc70-ffffffff8100dcc1: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e450)
Location: arch/x86/events/intel/ds.c:305
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100e450-ffffffff8100e49c: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e920)
Location: arch/x86/events/intel/ds.c:305
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100e920-ffffffff8100e96c: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f1f0)
Location: arch/x86/events/intel/ds.c:305
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100f1f0-ffffffff8100f23c: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f8a0)
Location: arch/x86/events/intel/ds.c:305
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100f8a0-ffffffff8100f8ec: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810127e4)
Location: arch/x86/events/intel/ds.c:306
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011404)
Location: arch/x86/events/intel/ds.c:306
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81012474)
Location: arch/x86/events/intel/ds.c:371
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810133b7)
Location: arch/x86/events/intel/ds.c:371
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810137a0)
Location: arch/x86/events/intel/ds.c:420
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff810137a0-ffffffff8101381c: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81017860)
Location: arch/x86/events/intel/ds.c:427
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff81017860-ffffffff810178dc: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81017200)
Location: arch/x86/events/intel/ds.c:475
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff81017200-ffffffff8101727c: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101cd40)
Location: arch/x86/events/intel/ds.c:480
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8101cd40-ffffffff8101cdbc: ds_clear_cea (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f8a0)
Location: arch/x86/events/intel/ds.c:305
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100f8a0-ffffffff8100f8ec: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e600)
Location: arch/x86/events/intel/ds.c:305
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100e600-ffffffff8100e64c: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f860)
Location: arch/x86/events/intel/ds.c:305
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100f860-ffffffff8100f8ac: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ds_clear_cea(void *cea, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fa30)
Location: arch/x86/events/intel/ds.c:305
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100fa30-ffffffff8100fa98: ds_clear_cea (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
