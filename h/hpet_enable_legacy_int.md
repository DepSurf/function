# Function: <code>hpet_enable_legacy_int</code>

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
In arch/x86/kernel/hpet.c (ffffffff8106226e)
Location: arch/x86/kernel/hpet.c:270
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_resume
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
In arch/x86/kernel/hpet.c (ffffffff8106209e)
Location: arch/x86/kernel/hpet.c:270
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_resume
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
In arch/x86/kernel/hpet.c (ffffffff81065134)
Location: arch/x86/kernel/hpet.c:270
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
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
In arch/x86/kernel/hpet.c (ffffffff81064a05)
Location: arch/x86/kernel/hpet.c:270
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
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
In arch/x86/kernel/hpet.c (ffffffff81068b96)
Location: arch/x86/kernel/hpet.c:270
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
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
In arch/x86/kernel/hpet.c (ffffffff826e9351)
Location: arch/x86/kernel/hpet.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
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
In arch/x86/kernel/hpet.c (ffffffff8289ff0d)
Location: arch/x86/kernel/hpet.c:267
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
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
In arch/x86/kernel/hpet.c (ffffffff828b7fef)
Location: arch/x86/kernel/hpet.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff828be4ed)
Location: arch/x86/kernel/hpet.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void hpet_enable_legacy_int();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107ca60)
Location: arch/x86/kernel/hpet.c:286
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_legacy_clockevent_register
```
**Symbols:**

```
ffffffff8107ca60-ffffffff8107ca89: hpet_enable_legacy_int (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void hpet_enable_legacy_int();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107c870)
Location: arch/x86/kernel/hpet.c:287
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_legacy_clockevent_register
```
**Symbols:**

```
ffffffff8107c870-ffffffff8107c899: hpet_enable_legacy_int (STB_LOCAL)
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
In arch/x86/kernel/hpet.c (ffffffff831da820)
Location: arch/x86/kernel/hpet.c:287
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff832bda2e)
Location: arch/x86/kernel/hpet.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff8346f41e)
Location: arch/x86/kernel/hpet.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff83e95a25)
Location: arch/x86/kernel/hpet.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff836b95a6)
Location: arch/x86/kernel/hpet.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff838e9ec8)
Location: arch/x86/kernel/hpet.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff828a94c3)
Location: arch/x86/kernel/hpet.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff828a156f)
Location: arch/x86/kernel/hpet.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff828bc3c2)
Location: arch/x86/kernel/hpet.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff828bf51a)
Location: arch/x86/kernel/hpet.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
