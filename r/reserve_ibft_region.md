# Function: <code>reserve_ibft_region</code>

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
In arch/x86/kernel/setup.c (ffffffff81f6639f)
Location: arch/x86/kernel/setup.c:656
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81f8e228)
Location: arch/x86/kernel/setup.c:659
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81fc95c6)
Location: arch/x86/kernel/setup.c:659
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff820a9cfd)
Location: arch/x86/kernel/setup.c:642
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826b081c)
Location: arch/x86/kernel/setup.c:627
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826d9ebd)
Location: arch/x86/kernel/setup.c:630
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828902a2)
Location: arch/x86/kernel/setup.c:630
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828a7a83)
Location: arch/x86/kernel/setup.c:646
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828aaad7)
Location: arch/x86/kernel/setup.c:646
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff82ccfed5)
Location: arch/x86/kernel/setup.c:598
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff82fbbd06)
Location: arch/x86/kernel/setup.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff831c61a1)
Location: arch/x86/kernel/setup.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reserve_ibft_region();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8330bf99)
Location: drivers/firmware/iscsi_ibft_find.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
```
**Symbols:**

```
ffffffff8330bf99-ffffffff8330c053: reserve_ibft_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reserve_ibft_region();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/iscsi_ibft_find.c (ffffffff834c58d4)
Location: drivers/firmware/iscsi_ibft_find.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
```
**Symbols:**

```
ffffffff834c58d4-ffffffff834c59c3: reserve_ibft_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reserve_ibft_region();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/iscsi_ibft_find.c (ffffffff83f06510)
Location: drivers/firmware/iscsi_ibft_find.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
```
**Symbols:**

```
ffffffff83f06510-ffffffff83f065d9: reserve_ibft_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reserve_ibft_region();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8372c4f0)
Location: drivers/firmware/iscsi_ibft_find.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff8372c4f0-ffffffff8372c5f7: reserve_ibft_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reserve_ibft_region();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/iscsi_ibft_find.c (ffffffff83960510)
Location: drivers/firmware/iscsi_ibft_find.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff83960510-ffffffff83960617: reserve_ibft_region (STB_GLOBAL)
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
In arch/x86/kernel/setup.c (ffffffff82898ae7)
Location: arch/x86/kernel/setup.c:646
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff82890df7)
Location: arch/x86/kernel/setup.c:646
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828abad7)
Location: arch/x86/kernel/setup.c:646
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828abae7)
Location: arch/x86/kernel/setup.c:646
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
