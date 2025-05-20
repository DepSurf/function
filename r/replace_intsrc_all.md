# Function: <code>replace_intsrc_all</code>

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
In arch/x86/kernel/mpparse.c (ffffffff81f70856)
Location: arch/x86/kernel/mpparse.c:723
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff81f98f87)
Location: arch/x86/kernel/mpparse.c:722
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff81fd4450)
Location: arch/x86/kernel/mpparse.c:725
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff820b513e)
Location: arch/x86/kernel/mpparse.c:725
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff826bb8b7)
Location: arch/x86/kernel/mpparse.c:742
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff826e55af)
Location: arch/x86/kernel/mpparse.c:746
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff8289c0d4)
Location: arch/x86/kernel/mpparse.c:745
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff828b3da5)
Location: arch/x86/kernel/mpparse.c:743
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff828b71fc)
Location: arch/x86/kernel/mpparse.c:743
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82cdc45c)
Location: arch/x86/kernel/mpparse.c:743
Inline: True
Direct callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
**Symbols:**

```
ffffffff82cdc45c-ffffffff82cdc60c: replace_intsrc_all.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82fc874d)
Location: arch/x86/kernel/mpparse.c:725
Inline: True
Direct callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
**Symbols:**

```
ffffffff82fc874d-ffffffff82fc88fd: replace_intsrc_all.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff831d2fdb)
Location: arch/x86/kernel/mpparse.c:725
Inline: True
Direct callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
**Symbols:**

```
ffffffff831d2fdb-ffffffff831d323f: replace_intsrc_all.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff832b5933)
Location: arch/x86/kernel/mpparse.c:726
Inline: True
Direct callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
**Symbols:**

```
ffffffff832b5933-ffffffff832b5d76: replace_intsrc_all.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff83467418)
Location: arch/x86/kernel/mpparse.c:726
Inline: True
Direct callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
**Symbols:**

```
ffffffff83467418-ffffffff83467735: replace_intsrc_all.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff83e8b090)
Location: arch/x86/kernel/mpparse.c:726
Inline: True
Direct callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
**Symbols:**

```
ffffffff83e8b090-ffffffff83e8b59b: replace_intsrc_all.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff836ae7f0)
Location: arch/x86/kernel/mpparse.c:726
Inline: True
Direct callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
**Symbols:**

```
ffffffff836ae7f0-ffffffff836aedb3: replace_intsrc_all.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff838ded70)
Location: arch/x86/kernel/mpparse.c:714
Inline: True
Direct callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
**Symbols:**

```
ffffffff838ded70-ffffffff838df333: replace_intsrc_all.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/mpparse.c (ffffffff828a5203)
Location: arch/x86/kernel/mpparse.c:743
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff8289d345)
Location: arch/x86/kernel/mpparse.c:743
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828b8113)
Location: arch/x86/kernel/mpparse.c:743
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff828b8214)
Location: arch/x86/kernel/mpparse.c:743
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
</details>
</li>
</ul>

## Differences
