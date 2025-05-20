# Function: <code>console_cpu_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int console_cpu_notify(struct notifier_block *self, long unsigned int action, void *hcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d8410)
Location: kernel/printk/printk.c:2117
Inline: False
```
**Symbols:**

```
ffffffff810d8410-ffffffff810d8444: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int console_cpu_notify(struct notifier_block *self, long unsigned int action, void *hcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ddb30)
Location: kernel/printk/printk.c:2187
Inline: False
```
**Symbols:**

```
ffffffff810ddb30-ffffffff810ddb64: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e4150)
Location: kernel/printk/printk.c:2069
Inline: False
```
**Symbols:**

```
ffffffff810e4150-ffffffff810e4173: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e30b0)
Location: kernel/printk/printk.c:2037
Inline: True
```
**Symbols:**

```
ffffffff810e30b0-ffffffff810e30e2: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810eaf90)
Location: kernel/printk/printk.c:2025
Inline: True
```
**Symbols:**

```
ffffffff810eaf90-ffffffff810eafc2: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f2ed0)
Location: kernel/printk/printk.c:2199
Inline: True
```
**Symbols:**

```
ffffffff810f2ed0-ffffffff810f2f02: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fe560)
Location: kernel/printk/printk.c:2202
Inline: True
```
**Symbols:**

```
ffffffff810fe560-ffffffff810fe592: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81106c50)
Location: kernel/printk/printk.c:2257
Inline: True
```
**Symbols:**

```
ffffffff81106c50-ffffffff81106c82: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81112fe0)
Location: kernel/printk/printk.c:2267
Inline: True
```
**Symbols:**

```
ffffffff81112fe0-ffffffff81113012: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111ef70)
Location: kernel/printk/printk.c:2287
Inline: True
```
**Symbols:**

```
ffffffff8111ef70-ffffffff8111ef9b: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119910)
Location: kernel/printk/printk.c:2371
Inline: True
```
**Symbols:**

```
ffffffff81119910-ffffffff8111993b: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111a490)
Location: kernel/printk/printk.c:2440
Inline: True
```
**Symbols:**

```
ffffffff8111a490-ffffffff8111a4bb: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113ae87)
Location: kernel/printk/printk.c:2501
Inline: True
```
**Symbols:**

```
ffffffff8113ae60-ffffffff8113ae9d: console_cpu_notify (STB_LOCAL)
ffffffff81cac411-ffffffff81cac425: console_cpu_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115d98f)
Location: kernel/printk/printk.c:2546
Inline: True
```
**Symbols:**

```
ffffffff8115d960-ffffffff8115d9d2: console_cpu_notify (STB_LOCAL)
ffffffff81e5c8cb-ffffffff81e5c8df: console_cpu_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119022f)
Location: kernel/printk/printk.c:2636
Inline: True
```
**Symbols:**

```
ffffffff81190200-ffffffff81190272: console_cpu_notify (STB_LOCAL)
ffffffff82058a66-ffffffff82058a7a: console_cpu_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a1a1f)
Location: kernel/printk/printk.c:2578
Inline: True
```
**Symbols:**

```
ffffffff811a19f0-ffffffff811a1a62: console_cpu_notify (STB_LOCAL)
ffffffff820d72e4-ffffffff820d72f8: console_cpu_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b2091)
Location: kernel/printk/printk.c:2594
Inline: True
```
**Symbols:**

```
ffffffff811b2060-ffffffff811b20e3: console_cpu_notify (STB_LOCAL)
ffffffff821b264e-ffffffff821b2662: console_cpu_notify.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff8000101744b8)
Location: kernel/printk/printk.c:2267
Inline: True
```
**Symbols:**

```
ffff8000101744b8-ffff8000101744f8: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c66b4)
Location: kernel/printk/printk.c:2267
Inline: True
```
**Symbols:**

```
c03c66b4-c03c66fc: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cd350)
Location: kernel/printk/printk.c:2267
Inline: True
```
**Symbols:**

```
c0000000001cd350-c0000000001cd3c8: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010f846)
Location: kernel/printk/printk.c:2267
Inline: True
```
**Symbols:**

```
ffffffe00010f846-ffffffe00010f88a: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b5c0)
Location: kernel/printk/printk.c:2267
Inline: True
```
**Symbols:**

```
ffffffff8110b5c0-ffffffff8110b5f2: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fc420)
Location: kernel/printk/printk.c:2267
Inline: True
```
**Symbols:**

```
ffffffff810fc420-ffffffff810fc452: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811094b0)
Location: kernel/printk/printk.c:2267
Inline: True
```
**Symbols:**

```
ffffffff811094b0-ffffffff811094e2: console_cpu_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int console_cpu_notify(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114c00)
Location: kernel/printk/printk.c:2267
Inline: True
```
**Symbols:**

```
ffffffff81114c00-ffffffff81114c41: console_cpu_notify (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>struct notifier_block *self</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int action</code>
</li>
<li>
<b>Param removed. </b>
<code>void *hcpu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
