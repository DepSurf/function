# Function: <code>__set_personality_x32</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102a200)
Location: arch/x86/kernel/process_64.c:542
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8102afcd)
Location: arch/x86/kernel/process_64.c:543
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8102c18c)
Location: arch/x86/kernel/process_64.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8102d23c)
Location: arch/x86/kernel/process_64.c:652
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8102f15c)
Location: arch/x86/kernel/process_64.c:643
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8102fabc)
Location: arch/x86/kernel/process_64.c:643
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __set_personality_x32();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032270)
Location: arch/x86/kernel/process_64.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
```
**Symbols:**

```
ffffffff81032270-ffffffff810322d1: __set_personality_x32 (STB_LOCAL)
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
In arch/x86/kernel/process_64.c (ffffffff81032d4c)
Location: arch/x86/kernel/process_64.c:657
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8103485c)
Location: arch/x86/kernel/process_64.c:657
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff81039b5c)
Location: arch/x86/kernel/process_64.c:683
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:682
Inline: True
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
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:683
Inline: True
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
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:684
Inline: True
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
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:686
Inline: True
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
In arch/x86/kernel/process_64.c (ffffffff8102fc1c)
Location: arch/x86/kernel/process_64.c:643
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8101f63c)
Location: arch/x86/kernel/process_64.c:643
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8102fa7c)
Location: arch/x86/kernel/process_64.c:643
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff810308cc)
Location: arch/x86/kernel/process_64.c:643
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
