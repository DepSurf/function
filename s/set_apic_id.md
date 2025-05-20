# Function: <code>set_apic_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a330)
Location: arch/x86/kernel/apic/apic_flat_64.c:126
Inline: False
```
**Symbols:**

```
ffffffff8105a330-ffffffff8105a340: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a570)
Location: arch/x86/kernel/apic/apic_flat_64.c:126
Inline: False
```
**Symbols:**

```
ffffffff8105a570-ffffffff8105a580: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d380)
Location: arch/x86/kernel/apic/apic_flat_64.c:122
Inline: False
```
**Symbols:**

```
ffffffff8105d380-ffffffff8105d390: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105caa0)
Location: arch/x86/kernel/apic/apic_flat_64.c:122
Inline: False
```
**Symbols:**

```
ffffffff8105caa0-ffffffff8105cab0: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810607e0)
Location: arch/x86/kernel/apic/apic_flat_64.c:122
Inline: False
```
**Symbols:**

```
ffffffff810607e0-ffffffff810607f0: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810638d0)
Location: arch/x86/kernel/apic/apic_flat_64.c:119
Inline: False
```
**Symbols:**

```
ffffffff810638d0-ffffffff810638e0: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810695d0)
Location: arch/x86/kernel/apic/apic_flat_64.c:120
Inline: False
```
**Symbols:**

```
ffffffff810695d0-ffffffff810695e0: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106cdd0)
Location: arch/x86/kernel/apic/apic_flat_64.c:120
Inline: False
```
**Symbols:**

```
ffffffff8106cdd0-ffffffff8106cde0: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d280)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:616
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e530)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff8106d280-ffffffff8106d28d: set_apic_id (STB_LOCAL)
ffffffff8106e530-ffffffff8106e540: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074400)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:650
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075a30)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff81074400-ffffffff8107440d: set_apic_id (STB_LOCAL)
ffffffff81075a30-ffffffff81075a40: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074f80)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:802
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076060)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff81074f80-ffffffff81074f8d: set_apic_id (STB_LOCAL)
ffffffff81076060-ffffffff81076070: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075a20)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:798
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076af0)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff81075a20-ffffffff81075a2d: set_apic_id (STB_LOCAL)
ffffffff81076af0-ffffffff81076b00: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81082ef0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:798
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81084250)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff81082ef0-ffffffff81082efd: set_apic_id (STB_LOCAL)
ffffffff81084250-ffffffff81084260: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092cb0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:804
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81094370)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff81092cb0-ffffffff81092cc3: set_apic_id (STB_LOCAL)
ffffffff81094370-ffffffff81094386: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a7f00)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:804
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9c50)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff810a7f00-ffffffff810a7f13: set_apic_id (STB_LOCAL)
ffffffff810a9c50-ffffffff810a9c66: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab170)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:805
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810ad010)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff810ab170-ffffffff810ab183: set_apic_id (STB_LOCAL)
ffffffff810ad010-ffffffff810ad026: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(u32 id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2060)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:782
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810b3ce0)
Location: arch/x86/kernel/apic/apic_flat_64.c:64
Inline: False
```
**Symbols:**

```
ffffffff810b2060-ffffffff810b2073: set_apic_id (STB_LOCAL)
ffffffff810b3ce0-ffffffff810b3cf6: set_apic_id (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d4d0)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff8106d4d0-ffffffff8106d4e0: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d910)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff8105d910-ffffffff8105d920: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d980)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff8106d980-ffffffff8106d990: set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
u32 set_apic_id(unsigned int id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e920)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:616
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fc00)
Location: arch/x86/kernel/apic/apic_flat_64.c:84
Inline: False
```
**Symbols:**

```
ffffffff8106e920-ffffffff8106e92d: set_apic_id (STB_LOCAL)
ffffffff8106fc00-ffffffff8106fc10: set_apic_id (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int id</code> ➡️ <code>u32 id</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
