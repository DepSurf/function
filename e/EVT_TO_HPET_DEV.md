# Function: <code>EVT_TO_HPET_DEV</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct hpet_dev *EVT_TO_HPET_DEV(struct clock_event_device *evtdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062df0)
Location: arch/x86/kernel/hpet.c:57
Inline: True
```
**Symbols:**

```
ffffffff81062df0-ffffffff81062df9: EVT_TO_HPET_DEV (STB_GLOBAL)
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
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:57
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
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:57
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
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:57
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
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:57
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
In arch/x86/kernel/hpet.c (ffffffff8106ac05)
Location: arch/x86/kernel/hpet.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_periodic
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
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
In arch/x86/kernel/hpet.c (ffffffff81070995)
Location: arch/x86/kernel/hpet.c:54
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_periodic
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
