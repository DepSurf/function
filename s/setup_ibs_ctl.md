# Function: <code>setup_ibs_ctl</code>

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
In arch/x86/events/amd/ibs.c (ffffffff81009807)
Location: arch/x86/events/amd/ibs.c:757
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff81009bf7)
Location: arch/x86/events/amd/ibs.c:824
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff81009c37)
Location: arch/x86/events/amd/ibs.c:824
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff810099ca)
Location: arch/x86/events/amd/ibs.c:825
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100973a)
Location: arch/x86/events/amd/ibs.c:825
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100a547)
Location: arch/x86/events/amd/ibs.c:829
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100a477)
Location: arch/x86/events/amd/ibs.c:829
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100a955)
Location: arch/x86/events/amd/ibs.c:825
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100a7c5)
Location: arch/x86/events/amd/ibs.c:827
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int setup_ibs_ctl(int ibs_eilvt_off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100b4b0)
Location: arch/x86/events/amd/ibs.c:827
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
**Symbols:**

```
ffffffff8100b4b0-ffffffff8100b5ab: setup_ibs_ctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int setup_ibs_ctl(int ibs_eilvt_off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a3f0)
Location: arch/x86/events/amd/ibs.c:870
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
**Symbols:**

```
ffffffff8100a3f0-ffffffff8100a4eb: setup_ibs_ctl (STB_LOCAL)
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
In arch/x86/events/amd/ibs.c (ffffffff8100b1e5)
Location: arch/x86/events/amd/ibs.c:870
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100b6d5)
Location: arch/x86/events/amd/ibs.c:874
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100c209)
Location: arch/x86/events/amd/ibs.c:1019
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100f1e9)
Location: arch/x86/events/amd/ibs.c:1345
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100e7c9)
Location: arch/x86/events/amd/ibs.c:1341
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff810140f9)
Location: arch/x86/events/amd/ibs.c:1350
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100a7c5)
Location: arch/x86/events/amd/ibs.c:827
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff810090c5)
Location: arch/x86/events/amd/ibs.c:827
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100a785)
Location: arch/x86/events/amd/ibs.c:827
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
In arch/x86/events/amd/ibs.c (ffffffff8100aea9)
Location: arch/x86/events/amd/ibs.c:827
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
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
