# Function: <code>smpboot_destroy_threads</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810a3a80)
Location: kernel/smpboot.c:258
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
**Symbols:**

```
ffffffff810a3a80-ffffffff810a3b13: smpboot_destroy_threads.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810a71a0)
Location: kernel/smpboot.c:260
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
**Symbols:**

```
ffffffff810a71a0-ffffffff810a7231: smpboot_destroy_threads.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810accb0)
Location: kernel/smpboot.c:265
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
**Symbols:**

```
ffffffff810accb0-ffffffff810acd4d: smpboot_destroy_threads.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810a98a0)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
**Symbols:**

```
ffffffff810a98a0-ffffffff810a9937: smpboot_destroy_threads.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810b0140)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
**Symbols:**

```
ffffffff810b0140-ffffffff810b01c6: smpboot_destroy_threads.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810b6f50)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
**Symbols:**

```
ffffffff810b6f50-ffffffff810b6fd8: smpboot_destroy_threads.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810c02e0)
Location: kernel/smpboot.c:265
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810c02e0-ffffffff810c0368: smpboot_destroy_threads.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810c63f0)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810c63f0-ffffffff810c6475: smpboot_destroy_threads.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810cf4d0)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810cf4d0-ffffffff810cf555: smpboot_destroy_threads.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void smpboot_destroy_threads(struct smp_hotplug_thread *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d9120)
Location: kernel/smpboot.c:266
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810d9120-ffffffff810d91c6: smpboot_destroy_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void smpboot_destroy_threads(struct smp_hotplug_thread *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d42c0)
Location: kernel/smpboot.c:267
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810d42c0-ffffffff810d4366: smpboot_destroy_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void smpboot_destroy_threads(struct smp_hotplug_thread *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d5f00)
Location: kernel/smpboot.c:266
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810d5f00-ffffffff810d5fa6: smpboot_destroy_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void smpboot_destroy_threads(struct smp_hotplug_thread *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810e9110)
Location: kernel/smpboot.c:266
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810e9110-ffffffff810e91eb: smpboot_destroy_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void smpboot_destroy_threads(struct smp_hotplug_thread *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff81103e90)
Location: kernel/smpboot.c:266
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff81103e90-ffffffff81103f77: smpboot_destroy_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void smpboot_destroy_threads(struct smp_hotplug_thread *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff81129610)
Location: kernel/smpboot.c:266
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff81129610-ffffffff81129703: smpboot_destroy_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void smpboot_destroy_threads(struct smp_hotplug_thread *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff81136ab0)
Location: kernel/smpboot.c:266
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff81136ab0-ffffffff81136ba3: smpboot_destroy_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void smpboot_destroy_threads(struct smp_hotplug_thread *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff81141ea0)
Location: kernel/smpboot.c:266
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff81141ea0-ffffffff81141f50: smpboot_destroy_threads (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffff80001012f300)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffff80001012f300-ffff80001012f3d8: smpboot_destroy_threads.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void smpboot_destroy_threads(struct smp_hotplug_thread *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (c037f07c)
Location: kernel/smpboot.c:266
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
c037f07c-c037f118: smpboot_destroy_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (c000000000178760)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
c000000000178760-c0000000001788b0: smpboot_destroy_threads.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffe0000e2ff0)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffe0000e2ff0-ffffffe0000e30bc: smpboot_destroy_threads.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810c9850)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810c9850-ffffffff810c98d5: smpboot_destroy_threads.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810b8070)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810b8070-ffffffff810b80f5: smpboot_destroy_threads.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810c8d80)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810c8d80-ffffffff810c8e05: smpboot_destroy_threads.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (ffffffff810d12f0)
Location: kernel/smpboot.c:266
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
**Symbols:**

```
ffffffff810d12f0-ffffffff810d1375: smpboot_destroy_threads.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
