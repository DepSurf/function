# Function: <code>nearby_node</code>

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
In arch/x86/kernel/cpu/amd.c (ffffffff8104309b)
Location: arch/x86/kernel/cpu/amd.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81043073)
Location: arch/x86/kernel/cpu/amd.c:276
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81042b3a)
Location: arch/x86/kernel/cpu/amd.c:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81040c41)
Location: arch/x86/kernel/cpu/amd.c:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81043e89)
Location: arch/x86/kernel/cpu/amd.c:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81046247)
Location: arch/x86/kernel/cpu/amd.c:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81047cc9)
Location: arch/x86/kernel/cpu/amd.c:283
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81048683)
Location: arch/x86/kernel/cpu/hygon.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a9f8)
Location: arch/x86/kernel/cpu/amd.c:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b43d)
Location: arch/x86/kernel/cpu/hygon.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b435)
Location: arch/x86/kernel/cpu/amd.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104be09)
Location: arch/x86/kernel/cpu/hygon.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int nearby_node(int apicid);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ebd0)
Location: arch/x86/kernel/cpu/amd.c:290
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:srat_detect_node
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104ff10)
Location: arch/x86/kernel/cpu/hygon.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:srat_detect_node
```
**Symbols:**

```
ffffffff8104ebd0-ffffffff8104ec68: nearby_node (STB_LOCAL)
ffffffff8104ff10-ffffffff8104ffa8: nearby_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int nearby_node(int apicid);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104de90)
Location: arch/x86/kernel/cpu/amd.c:290
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:srat_detect_node
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f120)
Location: arch/x86/kernel/cpu/hygon.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:srat_detect_node
```
**Symbols:**

```
ffffffff8104de90-ffffffff8104df28: nearby_node (STB_LOCAL)
ffffffff8104f120-ffffffff8104f1b8: nearby_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8105089b)
Location: arch/x86/kernel/cpu/amd.c:290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810512a6)
Location: arch/x86/kernel/cpu/hygon.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81058bfe)
Location: arch/x86/kernel/cpu/amd.c:290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81059781)
Location: arch/x86/kernel/cpu/hygon.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81065587)
Location: arch/x86/kernel/cpu/amd.c:290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065e3e)
Location: arch/x86/kernel/cpu/hygon.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81074888)
Location: arch/x86/kernel/cpu/amd.c:290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107517a)
Location: arch/x86/kernel/cpu/hygon.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff810767d0)
Location: arch/x86/kernel/cpu/amd.c:362
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810772ea)
Location: arch/x86/kernel/cpu/hygon.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8107dd66)
Location: arch/x86/kernel/cpu/amd.c:285
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e883)
Location: arch/x86/kernel/cpu/hygon.c:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b5a5)
Location: arch/x86/kernel/cpu/amd.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bf79)
Location: arch/x86/kernel/cpu/hygon.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8103aa02)
Location: arch/x86/kernel/cpu/amd.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103b17c)
Location: arch/x86/kernel/cpu/hygon.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b3e5)
Location: arch/x86/kernel/cpu/amd.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bdb9)
Location: arch/x86/kernel/cpu/hygon.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c7f5)
Location: arch/x86/kernel/cpu/amd.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104d1c9)
Location: arch/x86/kernel/cpu/hygon.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
