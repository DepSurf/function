# Function: <code>threshold_restart_bank</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81047b60)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81047b60-ffffffff81047ccd: threshold_restart_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81047c20)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:197
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81047c20-ffffffff81047d74: threshold_restart_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049870)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81049870-ffffffff810499c4: threshold_restart_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049210)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81049210-ffffffff8104936a: threshold_restart_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104cc50)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8104cc50-ffffffff8104cdaa: threshold_restart_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:338
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8104f920-ffffffff8104fa43: threshold_restart_bank (STB_LOCAL)
ffffffff81051523-ffffffff8105157b: threshold_restart_bank.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:339
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8104cfe0-ffffffff8104d103: threshold_restart_bank (STB_LOCAL)
ffffffff8104ebca-ffffffff8104ec22: threshold_restart_bank.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8104ff30-ffffffff81050053: threshold_restart_bank (STB_LOCAL)
ffffffff81051c87-ffffffff81051cdf: threshold_restart_bank.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff810508a0-ffffffff810509c3: threshold_restart_bank (STB_LOCAL)
ffffffff8105258e-ffffffff810525e6: threshold_restart_bank.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056146)
Location: arch/x86/kernel/cpu/mce/amd.c:384
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81055b30-ffffffff81055b4e: threshold_restart_bank (STB_LOCAL)
ffffffff81055a10-ffffffff81055b2c: threshold_restart_bank.part.0 (STB_LOCAL)
ffffffff81056ed1-ffffffff81056f29: threshold_restart_bank.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055046)
Location: arch/x86/kernel/cpu/mce/amd.c:384
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81054a30-ffffffff81054a4e: threshold_restart_bank (STB_LOCAL)
ffffffff81054900-ffffffff81054a24: threshold_restart_bank.part.0 (STB_LOCAL)
ffffffff81bd59cb-ffffffff81bd5a16: threshold_restart_bank.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810565d6)
Location: arch/x86/kernel/cpu/mce/amd.c:384
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81056230-ffffffff8105624e: threshold_restart_bank (STB_LOCAL)
ffffffff81056110-ffffffff81056230: threshold_restart_bank.part.0 (STB_LOCAL)
ffffffff81bc7e2a-ffffffff81bc7e79: threshold_restart_bank.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:397
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8105ec80-ffffffff8105edc6: threshold_restart_bank (STB_LOCAL)
ffffffff81c9ba7b-ffffffff81c9badc: threshold_restart_bank.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8106b0f0-ffffffff8106b25e: threshold_restart_bank (STB_LOCAL)
ffffffff81e4ae96-ffffffff81e4aef7: threshold_restart_bank.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8107b060-ffffffff8107b213: threshold_restart_bank (STB_LOCAL)
ffffffff82052e75-ffffffff82052e8e: threshold_restart_bank.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:422
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8107d300-ffffffff8107d4b3: threshold_restart_bank (STB_LOCAL)
ffffffff820d13b9-ffffffff820d13d2: threshold_restart_bank.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81084af0-ffffffff81084ca3: threshold_restart_bank (STB_LOCAL)
ffffffff821abf2d-ffffffff821abf46: threshold_restart_bank.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff810509a0-ffffffff81050ac3: threshold_restart_bank (STB_LOCAL)
ffffffff8105268e-ffffffff810526e6: threshold_restart_bank.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81040bc0-ffffffff81040d14: threshold_restart_bank (STB_LOCAL)
ffffffff81042125-ffffffff8104217e: threshold_restart_bank.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81050850-ffffffff81050973: threshold_restart_bank (STB_LOCAL)
ffffffff8105253e-ffffffff81052596: threshold_restart_bank.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void threshold_restart_bank(void *_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81051c90-ffffffff81051db3: threshold_restart_bank (STB_LOCAL)
ffffffff8105397e-ffffffff810539d6: threshold_restart_bank.cold (STB_LOCAL)
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
