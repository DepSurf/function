# Function: <code>uncore_insert_box_info</code>

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
In <code>5.0</code>: Absent ⚠️
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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void uncore_insert_box_info(struct uncore_unit_discovery *unit, int die, bool parsed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: arch/x86/events/intel/uncore_discovery.c:136
Inline: False
```
**Symbols:**

```
ffffffff81021c50-ffffffff81021f62: uncore_insert_box_info (STB_LOCAL)
ffffffff81bc48c8-ffffffff81bc48df: uncore_insert_box_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void uncore_insert_box_info(struct uncore_unit_discovery *unit, int die, bool parsed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: arch/x86/events/intel/uncore_discovery.c:136
Inline: False
```
**Symbols:**

```
ffffffff810257a0-ffffffff81025ad3: uncore_insert_box_info (STB_LOCAL)
ffffffff81c96e04-ffffffff81c96e1b: uncore_insert_box_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void uncore_insert_box_info(struct uncore_unit_discovery *unit, int die, bool parsed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: arch/x86/events/intel/uncore_discovery.c:136
Inline: False
```
**Symbols:**

```
ffffffff81029770-ffffffff81029ab0: uncore_insert_box_info (STB_LOCAL)
ffffffff81e4625e-ffffffff81e46275: uncore_insert_box_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uncore_insert_box_info(struct uncore_unit_discovery *unit, int die, bool parsed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810301e0)
Location: arch/x86/events/intel/uncore_discovery.c:136
Inline: False
```
**Symbols:**

```
ffffffff810301e0-ffffffff81030537: uncore_insert_box_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uncore_insert_box_info(struct uncore_unit_discovery *unit, int die, bool parsed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810302d0)
Location: arch/x86/events/intel/uncore_discovery.c:124
Inline: False
```
**Symbols:**

```
ffffffff810302d0-ffffffff81030622: uncore_insert_box_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uncore_insert_box_info(struct uncore_unit_discovery *unit, int die, bool parsed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036570)
Location: arch/x86/events/intel/uncore_discovery.c:124
Inline: False
```
**Symbols:**

```
ffffffff81036570-ffffffff810368f3: uncore_insert_box_info (STB_LOCAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
