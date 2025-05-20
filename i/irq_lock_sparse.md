# Function: <code>irq_lock_sparse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810da2d0)
Location: kernel/irq/irqdesc.c:134
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810da2d0-ffffffff810da2e7: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810dfb3c)
Location: kernel/irq/irqdesc.c:156
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - kernel/cpu.c:takedown_cpu
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810df7d0-ffffffff810df7e7: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e64cc)
Location: kernel/irq/irqdesc.c:332
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810e60b0-ffffffff810e60c7: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5b1c)
Location: kernel/irq/irqdesc.c:347
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810e5700-ffffffff810e5717: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810edd6c)
Location: kernel/irq/irqdesc.c:345
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810ed9c0-ffffffff810ed9d7: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f61b5)
Location: kernel/irq/irqdesc.c:362
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810f5e00-ffffffff810f5e17: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828adb83)
Location: kernel/irq/irqdesc.c:362
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81101590-ffffffff811015a7: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828c64ef)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81109d90-ffffffff81109da7: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828ceb1c)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81116160-ffffffff81116177: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff82ceff75)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81121e10-ffffffff81121e27: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff82fdc960)
Location: kernel/irq/irqdesc.c:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8111de90-ffffffff8111dea7: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff831e76ca)
Location: kernel/irq/irqdesc.c:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8111e120-ffffffff8111e137: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff832cb7bc)
Location: kernel/irq/irqdesc.c:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8113e5a0-ffffffff8113e5b7: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8347ef83)
Location: kernel/irq/irqdesc.c:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811619e0-ffffffff811619fd: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff83eab225)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811950c0-ffffffff811950dd: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff836d01e5)
Location: kernel/irq/irqdesc.c:402
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811a6a50-ffffffff811a6a6d: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff83901605)
Location: kernel/irq/irqdesc.c:402
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811b6570-ffffffff811b658d: irq_lock_sparse (STB_GLOBAL)
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
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff8000114464e0)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffff800010177b80-ffff800010177ba8: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c1520b68)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
c03c9558-c03c957c: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c00000000136b29c)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
c0000000001d16f0-c0000000001d172c: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe000008056)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffe000112948-ffffffe000112972: irq_lock_sparse (STB_GLOBAL)
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
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828b7814)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8110e740-ffffffff8110e757: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828afa94)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810ff490-ffffffff810ff4a7: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828ca750)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8110c630-ffffffff8110c647: irq_lock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void irq_lock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828cfb49)
Location: kernel/irq/irqdesc.c:377
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81117b40-ffffffff81117b57: irq_lock_sparse (STB_GLOBAL)
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
