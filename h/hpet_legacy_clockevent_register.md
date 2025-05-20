# Function: <code>hpet_legacy_clockevent_register</code>

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
In arch/x86/kernel/hpet.c (ffffffff81f74151)
Location: arch/x86/kernel/hpet.c:279
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
In arch/x86/kernel/hpet.c (ffffffff81f9c9a2)
Location: arch/x86/kernel/hpet.c:279
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
In arch/x86/kernel/hpet.c (ffffffff81fd7eed)
Location: arch/x86/kernel/hpet.c:279
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
In arch/x86/kernel/hpet.c (ffffffff820b8d2a)
Location: arch/x86/kernel/hpet.c:279
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
In arch/x86/kernel/hpet.c (ffffffff826bf574)
Location: arch/x86/kernel/hpet.c:279
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
In arch/x86/kernel/hpet.c (ffffffff826e9351)
Location: arch/x86/kernel/hpet.c:280
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
Location: arch/x86/kernel/hpet.c:276
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff828b7f55)
Location: arch/x86/kernel/hpet.c:415
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
In arch/x86/kernel/hpet.c (ffffffff828be453)
Location: arch/x86/kernel/hpet.c:415
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hpet_legacy_clockevent_register(struct hpet_channel *hc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff82ce250a)
Location: arch/x86/kernel/hpet.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
**Symbols:**

```
ffffffff82ce250a-ffffffff82ce2597: hpet_legacy_clockevent_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hpet_legacy_clockevent_register(struct hpet_channel *hc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff82fcf72e)
Location: arch/x86/kernel/hpet.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
**Symbols:**

```
ffffffff82fcf72e-ffffffff82fcf7bb: hpet_legacy_clockevent_register (STB_LOCAL)
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
In arch/x86/kernel/hpet.c (ffffffff831da784)
Location: arch/x86/kernel/hpet.c:416
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
In arch/x86/kernel/hpet.c (ffffffff832bd972)
Location: arch/x86/kernel/hpet.c:417
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
In arch/x86/kernel/hpet.c (ffffffff8346f362)
Location: arch/x86/kernel/hpet.c:417
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
In arch/x86/kernel/hpet.c (ffffffff83e95974)
Location: arch/x86/kernel/hpet.c:417
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
In arch/x86/kernel/hpet.c (ffffffff836b94f5)
Location: arch/x86/kernel/hpet.c:417
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
In arch/x86/kernel/hpet.c (ffffffff838e9e1a)
Location: arch/x86/kernel/hpet.c:417
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
In arch/x86/kernel/hpet.c (ffffffff828a9429)
Location: arch/x86/kernel/hpet.c:415
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
In arch/x86/kernel/hpet.c (ffffffff828a14d5)
Location: arch/x86/kernel/hpet.c:415
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
In arch/x86/kernel/hpet.c (ffffffff828bc328)
Location: arch/x86/kernel/hpet.c:415
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
In arch/x86/kernel/hpet.c (ffffffff828bf480)
Location: arch/x86/kernel/hpet.c:415
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
