# Function: <code>bringup_hibernate_cpu</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int bringup_hibernate_cpu(unsigned int sleep_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1316
Inline: False
```
**Symbols:**

```
ffffffff810ab881-ffffffff810ab8b9: bringup_hibernate_cpu.cold (STB_LOCAL)
ffffffff810ab180-ffffffff810ab1a7: bringup_hibernate_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int bringup_hibernate_cpu(unsigned int sleep_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1320
Inline: False
```
**Symbols:**

```
ffffffff81bdb4f2-ffffffff81bdb52a: bringup_hibernate_cpu.cold (STB_LOCAL)
ffffffff810a6a10-ffffffff810a6a37: bringup_hibernate_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int bringup_hibernate_cpu(unsigned int sleep_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1424
Inline: False
```
**Symbols:**

```
ffffffff81bcd5e4-ffffffff81bcd61c: bringup_hibernate_cpu.cold (STB_LOCAL)
ffffffff810a7ac0-ffffffff810a7ae7: bringup_hibernate_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bringup_hibernate_cpu(unsigned int sleep_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1454
Inline: False
```
**Symbols:**

```
ffffffff81ca3f25-ffffffff81ca3f5d: bringup_hibernate_cpu.cold (STB_LOCAL)
ffffffff810b9520-ffffffff810b9547: bringup_hibernate_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bringup_hibernate_cpu(unsigned int sleep_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1466
Inline: False
```
**Symbols:**

```
ffffffff81e53794-ffffffff81e537ca: bringup_hibernate_cpu.cold (STB_LOCAL)
ffffffff810cff50-ffffffff810cff7c: bringup_hibernate_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bringup_hibernate_cpu(unsigned int sleep_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ee3a0)
Location: kernel/cpu.c:1490
Inline: False
```
**Symbols:**

```
ffffffff810ee3a0-ffffffff810ee3f7: bringup_hibernate_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bringup_hibernate_cpu(unsigned int sleep_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810fa400)
Location: kernel/cpu.c:1772
Inline: False
```
**Symbols:**

```
ffffffff810fa400-ffffffff810fa45e: bringup_hibernate_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bringup_hibernate_cpu(unsigned int sleep_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81103820)
Location: kernel/cpu.c:1807
Inline: False
```
**Symbols:**

```
ffffffff81103820-ffffffff8110387e: bringup_hibernate_cpu (STB_GLOBAL)
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
