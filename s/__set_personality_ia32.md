# Function: <code>__set_personality_ia32</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102a1ac)
Location: arch/x86/kernel/process_64.c:563
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
In arch/x86/kernel/process_64.c (ffffffff8102af7c)
Location: arch/x86/kernel/process_64.c:564
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
In arch/x86/kernel/process_64.c (ffffffff8102c1db)
Location: arch/x86/kernel/process_64.c:588
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
In arch/x86/kernel/process_64.c (ffffffff8102d28b)
Location: arch/x86/kernel/process_64.c:673
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
In arch/x86/kernel/process_64.c (ffffffff8102f1ab)
Location: arch/x86/kernel/process_64.c:664
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
In arch/x86/kernel/process_64.c (ffffffff8102fb0b)
Location: arch/x86/kernel/process_64.c:664
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
void __set_personality_ia32();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810322e0)
Location: arch/x86/kernel/process_64.c:575
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
```
**Symbols:**

```
ffffffff810322e0-ffffffff81032343: __set_personality_ia32 (STB_LOCAL)
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
In arch/x86/kernel/process_64.c (ffffffff81032d8e)
Location: arch/x86/kernel/process_64.c:677
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
In arch/x86/kernel/process_64.c (ffffffff8103489e)
Location: arch/x86/kernel/process_64.c:677
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
In arch/x86/kernel/process_64.c (ffffffff81039b9e)
Location: arch/x86/kernel/process_64.c:703
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
In arch/x86/kernel/process_64.c (ffffffff81040a78)
Location: arch/x86/kernel/process_64.c:702
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff81049d88)
Location: arch/x86/kernel/process_64.c:703
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8104a3a8)
Location: arch/x86/kernel/process_64.c:704
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff81051608)
Location: arch/x86/kernel/process_64.c:706
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
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
In arch/x86/kernel/process_64.c (ffffffff8102fc6b)
Location: arch/x86/kernel/process_64.c:664
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
In arch/x86/kernel/process_64.c (ffffffff8101f68b)
Location: arch/x86/kernel/process_64.c:664
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
In arch/x86/kernel/process_64.c (ffffffff8102facb)
Location: arch/x86/kernel/process_64.c:664
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
In arch/x86/kernel/process_64.c (ffffffff8103091b)
Location: arch/x86/kernel/process_64.c:664
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
