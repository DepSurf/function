# Function: <code>smpboot_register_percpu_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81f7b9bc)
Location: include/linux/smpboot.h:51
Inline: True
```
```
In kernel/stop_machine.c (ffffffff81f821ae)
Location: include/linux/smpboot.h:51
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81fa45bc)
Location: include/linux/smpboot.h:51
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/softirq.c (ffffffff81fa4753)
Location: include/linux/smpboot.h:51
Inline: True
```
```
In kernel/stop_machine.c (ffffffff81fab73f)
Location: include/linux/smpboot.h:51
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81fdff6c)
Location: include/linux/smpboot.h:51
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/softirq.c (ffffffff81fe0116)
Location: include/linux/smpboot.h:51
Inline: True
```
```
In kernel/stop_machine.c (ffffffff81fe7a35)
Location: include/linux/smpboot.h:51
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff820c0d6b)
Location: include/linux/smpboot.h:51
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/softirq.c (ffffffff820c0f2a)
Location: include/linux/smpboot.h:51
Inline: True
```
```
In kernel/stop_machine.c (ffffffff820c808b)
Location: include/linux/smpboot.h:51
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff826c8f66)
Location: include/linux/smpboot.h:52
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/softirq.c (ffffffff826c9125)
Location: include/linux/smpboot.h:52
Inline: True
```
```
In kernel/stop_machine.c (ffffffff826d0749)
Location: include/linux/smpboot.h:52
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff826f306b)
Location: include/linux/smpboot.h:52
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/softirq.c (ffffffff826f32c9)
Location: include/linux/smpboot.h:52
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/stop_machine.c (ffffffff826faec4)
Location: include/linux/smpboot.h:52
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c0370)
Location: kernel/smpboot.c:288
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff810c0370-ffffffff810c045b: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c6480)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff810c6480-ffffffff810c655b: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810cf560)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff810cf560-ffffffff810cf63b: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d9360)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff810d9360-ffffffff810d943b: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d4510)
Location: kernel/smpboot.c:290
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff810d4510-ffffffff810d45eb: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d6150)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff810d6150-ffffffff810d622b: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff81ca5903-ffffffff81ca5917: smpboot_register_percpu_thread.cold (STB_LOCAL)
ffffffff810e93e0-ffffffff810e950e: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff81e551fc-ffffffff81e55211: smpboot_register_percpu_thread.cold (STB_LOCAL)
ffffffff811041a0-ffffffff811042ab: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff82056897-ffffffff820568ac: smpboot_register_percpu_thread.cold (STB_LOCAL)
ffffffff81129960-ffffffff81129a76: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff820d4f06-ffffffff820d4f1b: smpboot_register_percpu_thread.cold (STB_LOCAL)
ffffffff81136e00-ffffffff81136f16: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:288
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff821afe01-ffffffff821afe16: smpboot_register_percpu_thread.cold (STB_LOCAL)
ffffffff81141fe0-ffffffff811420f6: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffff80001012f3d8)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffff80001012f3d8-ffff80001012f504: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (c037f26c)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
c037f26c-c037f364: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (c000000000178b30)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
c000000000178b30-c000000000178ccc: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffe0000e30bc)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
```
**Symbols:**

```
ffffffe0000e30bc-ffffffe0000e31c0: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c98e0)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
```
**Symbols:**

```
ffffffff810c98e0-ffffffff810c99bb: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b8100)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
```
**Symbols:**

```
ffffffff810b8100-ffffffff810b81db: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c8e10)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff810c8e10-ffffffff810c8eeb: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smpboot_register_percpu_thread(struct smp_hotplug_thread *plug_thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d1380)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/stop_machine.c:cpu_stop_init
  - drivers/powercap/idle_inject.c:idle_inject_init
```
**Symbols:**

```
ffffffff810d1380-ffffffff810d145b: smpboot_register_percpu_thread (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
