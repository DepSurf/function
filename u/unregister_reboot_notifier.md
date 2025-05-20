# Function: <code>unregister_reboot_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a2840)
Location: kernel/reboot.c:101
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810a2840-ffffffff810a285a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a5f50)
Location: kernel/reboot.c:101
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810a5f50-ffffffff810a5f6a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810abbb0)
Location: kernel/reboot.c:101
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810abbb0-ffffffff810abbca: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a8780)
Location: kernel/reboot.c:101
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810a8780-ffffffff810a879a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810aef30)
Location: kernel/reboot.c:101
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810aef30-ffffffff810aef4a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b5d70)
Location: kernel/reboot.c:101
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810b5d70-ffffffff810b5d8a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810bf000)
Location: kernel/reboot.c:102
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810bf000-ffffffff810bf01a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c5110)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810c5110-ffffffff810c512a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810ce210)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810ce210-ffffffff810ce22a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d7fe0)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810d7fe0-ffffffff810d7ffa: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d2e40)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810d2e40-ffffffff810d2e5a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d4b40)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810d4b40-ffffffff810d4b5a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810e7db5)
Location: kernel/reboot.c:105
Inline: True
Inline callers:
  - kernel/reboot.c:devm_unregister_reboot_notifier
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810e7d00-ffffffff810e7d1a: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81102155)
Location: kernel/reboot.c:114
Inline: True
Inline callers:
  - kernel/reboot.c:devm_unregister_reboot_notifier
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff81102070-ffffffff81102092: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff811273f5)
Location: kernel/reboot.c:114
Inline: True
Inline callers:
  - kernel/reboot.c:devm_unregister_reboot_notifier
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff811272f0-ffffffff81127312: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81134895)
Location: kernel/reboot.c:114
Inline: True
Inline callers:
  - kernel/reboot.c:devm_unregister_reboot_notifier
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff81134790-ffffffff811347b2: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff8113f885)
Location: kernel/reboot.c:124
Inline: True
Inline callers:
  - kernel/reboot.c:devm_unregister_reboot_notifier
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff8113f780-ffffffff8113f7a2: unregister_reboot_notifier (STB_GLOBAL)
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
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffff80001012dba8)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - virt/kvm/kvm_main.c:kvm_exit
  - virt/kvm/kvm_main.c:kvm_init
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
  - drivers/firmware/arm_sdei.c:sdei_probe
```
**Symbols:**

```
ffff80001012dba8-ffff80001012dbdc: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c037da4c)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
c037da4c-c037da74: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c000000000176a1c)
Location: kernel/reboot.c:104
Inline: True
Inline callers:
  - kernel/reboot.c:devm_unregister_reboot_notifier
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_exit
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
```
**Symbols:**

```
c0000000001769c0-c000000000176a00: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffe0000e1c76)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffe0000e1c76-ffffffe0000e1ca8: unregister_reboot_notifier (STB_GLOBAL)
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
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c8590)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810c8590-ffffffff810c85aa: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b6db0)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810b6db0-ffffffff810b6dca: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c7ac0)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810c7ac0-ffffffff810c7ada: unregister_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int unregister_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810cffb0)
Location: kernel/reboot.c:104
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff810cffb0-ffffffff810cffca: unregister_reboot_notifier (STB_GLOBAL)
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
