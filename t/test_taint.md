# Function: <code>test_taint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81080be0)
Location: kernel/panic.c:288
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff81080be0-ffffffff81080bf7: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8119e703)
Location: kernel/panic.c:337
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff81082b00-ffffffff81082b1a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff811ae12f)
Location: kernel/panic.c:367
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff81087560-ffffffff8108757a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108485e)
Location: kernel/panic.c:369
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff81084300-ffffffff8108431a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108b317)
Location: kernel/panic.c:374
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff8108ac00-ffffffff8108ac1a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108ea97)
Location: kernel/panic.c:363
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff8108e470-ffffffff8108e48a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81096df1)
Location: kernel/panic.c:398
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff81096700-ffffffff8109671a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109b36d)
Location: kernel/panic.c:403
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff8109ac60-ffffffff8109ac7a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a188d)
Location: kernel/panic.c:412
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810a1180-ffffffff810a119a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a86a6)
Location: kernel/panic.c:422
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_modinfo
  - kernel/module.c:set_license
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff810a8080-ffffffff810a809a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81bdb25e)
Location: kernel/panic.c:422
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_modinfo
  - kernel/module.c:set_license
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff810a3dd0-ffffffff810a3dea: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81bcd350)
Location: kernel/panic.c:422
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff810a4a20-ffffffff810a4a3a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81ca3b21)
Location: kernel/panic.c:420
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff810b6240-ffffffff810b625a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81e532f3)
Location: kernel/panic.c:464
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff810cc720-ffffffff810cc740: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ea43f)
Location: kernel/panic.c:515
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff810e9ea0-ffffffff810e9ec0: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810f604c)
Location: kernel/panic.c:515
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff810f5aa0-ffffffff810f5ac0: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ff3dc)
Location: kernel/panic.c:519
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
**Symbols:**

```
ffffffff810fee50-ffffffff810fee70: test_taint (STB_GLOBAL)
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
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffff8000100f6a94)
Location: kernel/panic.c:412
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffff8000100f6048-ffff8000100f6094: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c0354a7c)
Location: kernel/panic.c:412
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
c03542dc-c035431c: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c00000000013c904)
Location: kernel/panic.c:412
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
c00000000013bd90-c00000000013bdcc: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffe0000c2640)
Location: kernel/panic.c:412
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffe0000c1e70-ffffffe0000c1eb2: test_taint (STB_GLOBAL)
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
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109b1ad)
Location: kernel/panic.c:412
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff8109aaa0-ffffffff8109aaba: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81089be7)
Location: kernel/panic.c:412
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810894e0-ffffffff810894fa: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109b15d)
Location: kernel/panic.c:412
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff8109aa50-ffffffff8109aa6a: test_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int test_taint(unsigned int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a2dd4)
Location: kernel/panic.c:412
Inline: True
Inline callers:
  - kernel/panic.c:panic
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810a26d0-ffffffff810a26ea: test_taint (STB_GLOBAL)
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
