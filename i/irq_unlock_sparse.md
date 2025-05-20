# Function: <code>irq_unlock_sparse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810da2f0)
Location: kernel/irq/irqdesc.c:139
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810da2f0-ffffffff810da307: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810dfb4f)
Location: kernel/irq/irqdesc.c:161
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810df7f0-ffffffff810df807: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e64df)
Location: kernel/irq/irqdesc.c:337
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810e60d0-ffffffff810e60e7: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5b2f)
Location: kernel/irq/irqdesc.c:352
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810e5720-ffffffff810e5737: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810edd7f)
Location: kernel/irq/irqdesc.c:350
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810ed9e0-ffffffff810ed9f7: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f61d8)
Location: kernel/irq/irqdesc.c:367
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810f5e20-ffffffff810f5e37: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828adbb5)
Location: kernel/irq/irqdesc.c:367
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811015b0-ffffffff811015c7: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828c651f)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81109db0-ffffffff81109dc7: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828ceb4c)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81116180-ffffffff81116197: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff82ceffa5)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81121e30-ffffffff81121e47: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff82fdc990)
Location: kernel/irq/irqdesc.c:384
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8111deb0-ffffffff8111dec7: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff831e76fa)
Location: kernel/irq/irqdesc.c:384
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8111e140-ffffffff8111e157: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff832cb7ec)
Location: kernel/irq/irqdesc.c:384
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8113e5c0-ffffffff8113e5d7: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8347efb3)
Location: kernel/irq/irqdesc.c:384
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81161a00-ffffffff81161a1d: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff83eab2cb)
Location: kernel/irq/irqdesc.c:387
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811950f0-ffffffff8119510d: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff836d028b)
Location: kernel/irq/irqdesc.c:407
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811a6a80-ffffffff811a6a9d: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff839016ab)
Location: kernel/irq/irqdesc.c:407
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811b65a0-ffffffff811b65bd: irq_unlock_sparse (STB_GLOBAL)
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
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800011446508)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffff800010177ba8-ffff800010177bd0: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c1520ba4)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
c03c957c-c03c95a0: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c00000000136b2e4)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
c0000000001d1730-c0000000001d176c: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe000008088)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffe000112972-ffffffe00011299c: irq_unlock_sparse (STB_GLOBAL)
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
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828b7844)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8110e760-ffffffff8110e777: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828afac4)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810ff4b0-ffffffff810ff4c7: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828ca780)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8110c650-ffffffff8110c667: irq_unlock_sparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void irq_unlock_sparse();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff828cfb79)
Location: kernel/irq/irqdesc.c:382
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81117b60-ffffffff81117b77: irq_unlock_sparse (STB_GLOBAL)
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
