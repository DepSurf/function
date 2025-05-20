# Function: <code>stop_machine_unpark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81f821ca)
Location: kernel/stop_machine.c:498
Inline: True
```
**Symbols:**

```
ffffffff81120870-ffffffff81120899: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81fab75f)
Location: kernel/stop_machine.c:504
Inline: True
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff811287c0-ffffffff811287e9: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81fe7a55)
Location: kernel/stop_machine.c:519
Inline: True
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff81132470-ffffffff81132499: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff820c80ab)
Location: kernel/stop_machine.c:519
Inline: True
Direct callers:
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81133920-ffffffff81133949: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff826d0769)
Location: kernel/stop_machine.c:519
Inline: True
Direct callers:
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff811406d0-ffffffff811406f9: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff826faee4)
Location: kernel/stop_machine.c:547
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8114f010-ffffffff8114f039: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff828b1e10)
Location: kernel/stop_machine.c:547
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8115bcf0-ffffffff8115bd19: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff828cab4d)
Location: kernel/stop_machine.c:555
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff811683b0-ffffffff811683d9: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff828d302f)
Location: kernel/stop_machine.c:559
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff81174270-ffffffff81174299: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811860b0)
Location: kernel/stop_machine.c:530
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/stop_machine.c:cpu_stop_init
```
**Symbols:**

```
ffffffff811860b0-ffffffff811860d9: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81183240)
Location: kernel/stop_machine.c:551
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/stop_machine.c:cpu_stop_init
```
**Symbols:**

```
ffffffff81183240-ffffffff81183269: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81184360)
Location: kernel/stop_machine.c:552
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/stop_machine.c:cpu_stop_init
```
**Symbols:**

```
ffffffff81184360-ffffffff81184389: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811ac660)
Location: kernel/stop_machine.c:552
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/stop_machine.c:cpu_stop_init
```
**Symbols:**

```
ffffffff811ac660-ffffffff811ac6a9: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811de130)
Location: kernel/stop_machine.c:550
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/stop_machine.c:cpu_stop_init
```
**Symbols:**

```
ffffffff811de130-ffffffff811de181: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff83eb16f8)
Location: kernel/stop_machine.c:550
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff81223c50-ffffffff81223ca1: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff836d66a8)
Location: kernel/stop_machine.c:550
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff8123a2b0-ffffffff8123a301: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff83908ae8)
Location: kernel/stop_machine.c:550
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff81253f80-ffffffff81253fd1: stop_machine_unpark (STB_GLOBAL)
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
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff80001144b63c)
Location: kernel/stop_machine.c:559
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffff8000101e8ae8-ffff8000101e8b34: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c1525b10)
Location: kernel/stop_machine.c:559
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
c0428b58-c0428b98: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0000000013710e4)
Location: kernel/stop_machine.c:559
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
c000000000259620-c00000000025967c: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00000c99a)
Location: kernel/stop_machine.c:559
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffe00015da9a-ffffffe00015dae2: stop_machine_unpark (STB_GLOBAL)
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
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff828bbee0)
Location: kernel/stop_machine.c:559
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff8116c890-ffffffff8116c8b9: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff828b4573)
Location: kernel/stop_machine.c:559
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff8115fa50-ffffffff8115fa79: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff828cec63)
Location: kernel/stop_machine.c:559
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff8116a660-ffffffff8116a689: stop_machine_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void stop_machine_unpark(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff828d405d)
Location: kernel/stop_machine.c:559
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
```
**Symbols:**

```
ffffffff81177dd0-ffffffff81177df9: stop_machine_unpark (STB_GLOBAL)
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
