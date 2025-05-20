# Function: <code>iosf_mbi_get_sem</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iosf_mbi_get_sem(u32 *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fbe0)
Location: arch/x86/platform/intel/iosf_mbi.c:233
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
```
**Symbols:**

```
ffffffff8108fbe0-ffffffff8108fc3e: iosf_mbi_get_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_get_sem(u32 *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:224
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
```
**Symbols:**

```
ffffffff81093860-ffffffff8109389b: iosf_mbi_get_sem (STB_LOCAL)
ffffffff81093c15-ffffffff81093c3a: iosf_mbi_get_sem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_get_sem(u32 *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: False
```
**Symbols:**

```
ffffffff81094650-ffffffff8109468b: iosf_mbi_get_sem (STB_LOCAL)
ffffffff81094b80-ffffffff81094ba5: iosf_mbi_get_sem.cold (STB_LOCAL)
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81099d4e)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: True
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81098e3e)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: True
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8109967e)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: True
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810a967e)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: True
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810bef78)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810dabae)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e613e)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810ee531)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_get_sem(u32 *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: False
```
**Symbols:**

```
ffffffff81093610-ffffffff8109364b: iosf_mbi_get_sem (STB_LOCAL)
ffffffff81093b40-ffffffff81093b65: iosf_mbi_get_sem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_get_sem(u32 *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: False
```
**Symbols:**

```
ffffffff810820a0-ffffffff810820db: iosf_mbi_get_sem (STB_LOCAL)
ffffffff810825d0-ffffffff810825f5: iosf_mbi_get_sem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_get_sem(u32 *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: False
```
**Symbols:**

```
ffffffff810935c0-ffffffff810935fb: iosf_mbi_get_sem (STB_LOCAL)
ffffffff81093af0-ffffffff81093b15: iosf_mbi_get_sem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_get_sem(u32 *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:247
Inline: False
```
**Symbols:**

```
ffffffff81095b10-ffffffff81095b4b: iosf_mbi_get_sem (STB_LOCAL)
ffffffff8109603e-ffffffff81096063: iosf_mbi_get_sem.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
