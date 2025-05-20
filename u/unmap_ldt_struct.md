# Function: <code>unmap_ldt_struct</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810347d5)
Location: arch/x86/kernel/ldt.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8103666f)
Location: arch/x86/kernel/ldt.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81036e9f)
Location: arch/x86/kernel/ldt.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unmap_ldt_struct(struct mm_struct *mm, struct ldt_struct *ldt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038a70)
Location: arch/x86/kernel/ldt.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
**Symbols:**

```
ffffffff81038a70-ffffffff81038b9f: unmap_ldt_struct (STB_LOCAL)
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
In arch/x86/kernel/ldt.c (ffffffff810396c3)
Location: arch/x86/kernel/ldt.c:349
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8103b195)
Location: arch/x86/kernel/ldt.c:349
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81040bc5)
Location: arch/x86/kernel/ldt.c:349
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8104850d)
Location: arch/x86/kernel/ldt.c:349
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8105326d)
Location: arch/x86/kernel/ldt.c:349
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81054247)
Location: arch/x86/kernel/ldt.c:349
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8105b477)
Location: arch/x86/kernel/ldt.c:349
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81036fff)
Location: arch/x86/kernel/ldt.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff810268f3)
Location: arch/x86/kernel/ldt.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81036e5f)
Location: arch/x86/kernel/ldt.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81037e5f)
Location: arch/x86/kernel/ldt.c:265
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
