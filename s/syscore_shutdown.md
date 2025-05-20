# Function: <code>syscore_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8154c630)
Location: drivers/base/syscore.c:117
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_power_off
```
**Symbols:**

```
ffffffff8154c630-ffffffff8154c698: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8159e420)
Location: drivers/base/syscore.c:117
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
```
**Symbols:**

```
ffffffff8159e420-ffffffff8159e48f: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815cc9d0)
Location: drivers/base/syscore.c:117
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
```
**Symbols:**

```
ffffffff815cc9d0-ffffffff815cca3f: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815e1530)
Location: drivers/base/syscore.c:117
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
```
**Symbols:**

```
ffffffff815e1530-ffffffff815e159f: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81648670)
Location: drivers/base/syscore.c:117
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
```
**Symbols:**

```
ffffffff81648670-ffffffff816486e2: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff81683c96-ffffffff81683ca7: syscore_shutdown.cold.8 (STB_LOCAL)
ffffffff81683bd0-ffffffff81683c38: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff816a3966-ffffffff816a3977: syscore_shutdown.cold.9 (STB_LOCAL)
ffffffff816a38a0-ffffffff816a3908: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff816dc85b-ffffffff816dc870: syscore_shutdown.cold (STB_LOCAL)
ffffffff816dc7a0-ffffffff816dc7fd: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff817008eb-ffffffff81700900: syscore_shutdown.cold (STB_LOCAL)
ffffffff81700830-ffffffff8170088d: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff817ba82e-ffffffff817ba843: syscore_shutdown.cold (STB_LOCAL)
ffffffff817ba770-ffffffff817ba7d0: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:114
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff81c0e478-ffffffff81c0e48d: syscore_shutdown.cold (STB_LOCAL)
ffffffff817cf430-ffffffff817cf490: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:114
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff81c00878-ffffffff81c0088d: syscore_shutdown.cold (STB_LOCAL)
ffffffff817b2e40-ffffffff817b2ea0: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:114
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff81d031a1-ffffffff81d031cf: syscore_shutdown.cold (STB_LOCAL)
ffffffff8183c320-ffffffff8183c390: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:114
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff81ecb8f5-ffffffff81ecb923: syscore_shutdown.cold (STB_LOCAL)
ffffffff8197eba0-ffffffff8197ec1a: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:114
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
```
**Symbols:**

```
ffffffff820986ca-ffffffff820986e3: syscore_shutdown.cold (STB_LOCAL)
ffffffff81aec250-ffffffff81aec2d8: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:114
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
```
**Symbols:**

```
ffffffff821196b6-ffffffff821196cf: syscore_shutdown.cold (STB_LOCAL)
ffffffff81b3a440-ffffffff81b3a4c8: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:114
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff821f7679-ffffffff821f7692: syscore_shutdown.cold (STB_LOCAL)
ffffffff81b91f00-ffffffff81b91f88: syscore_shutdown (STB_GLOBAL)
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
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffff8000108ebc60)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffff8000108ebc60-ffff8000108ebcfc: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c09d9cdc)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
c09d9cdc-c09d9d68: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c0000000009834a0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
c0000000009834a0-c00000000098357c: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffe00057f366)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffe00057f366-ffffffe00057f3f0: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff816c60db-ffffffff816c60f0: syscore_shutdown.cold (STB_LOCAL)
ffffffff816c6020-ffffffff816c607d: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff816a133b-ffffffff816a1350: syscore_shutdown.cold (STB_LOCAL)
ffffffff816a1280-ffffffff816a12dd: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff816f45ab-ffffffff816f45c0: syscore_shutdown.cold (STB_LOCAL)
ffffffff816f44f0-ffffffff816f454d: syscore_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void syscore_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:116
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff8170ee3b-ffffffff8170ee50: syscore_shutdown.cold (STB_LOCAL)
ffffffff8170ed80-ffffffff8170eddd: syscore_shutdown (STB_GLOBAL)
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
