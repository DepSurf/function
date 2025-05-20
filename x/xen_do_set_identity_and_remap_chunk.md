# Function: <code>xen_do_set_identity_and_remap_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81f61dc7)
Location: arch/x86/xen/setup.c:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81f88e3c)
Location: arch/x86/xen/setup.c:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81fc4230)
Location: arch/x86/xen/setup.c:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff820a42e2)
Location: arch/x86/xen/setup.c:331
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff826aa9bb)
Location: arch/x86/xen/setup.c:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff826d3b2e)
Location: arch/x86/xen/setup.c:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82889bc1)
Location: arch/x86/xen/setup.c:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a0f61)
Location: arch/x86/xen/setup.c:333
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a4031)
Location: arch/x86/xen/setup.c:333
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_do_set_identity_and_remap_chunk(long unsigned int start_pfn, long unsigned int size, long unsigned int remap_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82cca303)
Location: arch/x86/xen/setup.c:334
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff82cca303-ffffffff82cca486: xen_do_set_identity_and_remap_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_do_set_identity_and_remap_chunk(long unsigned int start_pfn, long unsigned int size, long unsigned int remap_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82fb6171)
Location: arch/x86/xen/setup.c:333
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff82fb6171-ffffffff82fb62f4: xen_do_set_identity_and_remap_chunk (STB_LOCAL)
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
In arch/x86/xen/setup.c (ffffffff831c0b39)
Location: arch/x86/xen/setup.c:333
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
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
In arch/x86/xen/setup.c (ffffffff832a13cb)
Location: arch/x86/xen/setup.c:333
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff834503fb)
Location: arch/x86/xen/setup.c:329
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff83e6c6f8)
Location: arch/x86/xen/setup.c:330
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8368d21b)
Location: arch/x86/xen/setup.c:331
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff838bcddb)
Location: arch/x86/xen/setup.c:334
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82892057)
Location: arch/x86/xen/setup.c:333
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a5031)
Location: arch/x86/xen/setup.c:333
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a5005)
Location: arch/x86/xen/setup.c:333
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
