# Function: <code>enter_uniprocessor</code>

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
In arch/x86/mm/mmio-mod.c (ffffffff810747a9)
Location: arch/x86/mm/mmio-mod.c:383
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff81075d84)
Location: arch/x86/mm/mmio-mod.c:383
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff81079929)
Location: arch/x86/mm/mmio-mod.c:383
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff810781c9)
Location: arch/x86/mm/mmio-mod.c:383
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff8107e525)
Location: arch/x86/mm/mmio-mod.c:383
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff81081595)
Location: arch/x86/mm/mmio-mod.c:382
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff810881a5)
Location: arch/x86/mm/mmio-mod.c:382
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff8108bdf3)
Location: arch/x86/mm/mmio-mod.c:370
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff8108ca63)
Location: arch/x86/mm/mmio-mod.c:370
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void enter_uniprocessor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:370
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
**Symbols:**

```
ffffffff81093c80-ffffffff81093d75: enter_uniprocessor (STB_LOCAL)
ffffffff8109428e-ffffffff810942f7: enter_uniprocessor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void enter_uniprocessor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:370
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
**Symbols:**

```
ffffffff810931d0-ffffffff810932c5: enter_uniprocessor (STB_LOCAL)
ffffffff81bda07f-ffffffff81bda0e8: enter_uniprocessor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void enter_uniprocessor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:368
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
**Symbols:**

```
ffffffff81093bd0-ffffffff81093cc5: enter_uniprocessor (STB_LOCAL)
ffffffff81bcc131-ffffffff81bcc19a: enter_uniprocessor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void enter_uniprocessor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:368
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
**Symbols:**

```
ffffffff810a39b0-ffffffff810a3aa5: enter_uniprocessor (STB_LOCAL)
ffffffff81ca20b8-ffffffff81ca2121: enter_uniprocessor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void enter_uniprocessor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:368
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
**Symbols:**

```
ffffffff810b8090-ffffffff810b8185: enter_uniprocessor (STB_LOCAL)
ffffffff81e51719-ffffffff81e51780: enter_uniprocessor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void enter_uniprocessor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff810d3780)
Location: arch/x86/mm/mmio-mod.c:368
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
**Symbols:**

```
ffffffff810d3780-ffffffff810d38c5: enter_uniprocessor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void enter_uniprocessor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff810d6b60)
Location: arch/x86/mm/mmio-mod.c:368
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
**Symbols:**

```
ffffffff810d6b60-ffffffff810d6ca5: enter_uniprocessor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void enter_uniprocessor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff810df390)
Location: arch/x86/mm/mmio-mod.c:368
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
**Symbols:**

```
ffffffff810df390-ffffffff810df4d5: enter_uniprocessor (STB_LOCAL)
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
In arch/x86/mm/mmio-mod.c (ffffffff8108ba23)
Location: arch/x86/mm/mmio-mod.c:370
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff8107a543)
Location: arch/x86/mm/mmio-mod.c:370
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b9d3)
Location: arch/x86/mm/mmio-mod.c:370
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
In arch/x86/mm/mmio-mod.c (ffffffff8108dd33)
Location: arch/x86/mm/mmio-mod.c:370
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
