# Function: <code>tboot_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e120)
Location: arch/x86/kernel/tboot.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_sleep
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
```
**Symbols:**

```
ffffffff8103e120-ffffffff8103e24a: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103df40)
Location: arch/x86/kernel/tboot.c:216
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_sleep
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8103df40-ffffffff8103e06d: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103d7f0)
Location: arch/x86/kernel/tboot.c:216
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_sleep
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8103d7f0-ffffffff8103d91c: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103b850)
Location: arch/x86/kernel/tboot.c:220
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8103b850-ffffffff8103b983: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e270)
Location: arch/x86/kernel/tboot.c:231
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8103e270-ffffffff8103e3a6: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:231
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8103fb99-ffffffff8103fba5: tboot_shutdown.cold.18 (STB_LOCAL)
ffffffff8103f800-ffffffff8103f935: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81040e2b)
Location: arch/x86/kernel/tboot.c:231
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81041199-ffffffff810411a5: tboot_shutdown.cold.18 (STB_LOCAL)
ffffffff81040e00-ffffffff81040f35: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8104351b)
Location: arch/x86/kernel/tboot.c:218
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81043881-ffffffff8104388d: tboot_shutdown.cold (STB_LOCAL)
ffffffff810434f0-ffffffff81043625: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81043c6b)
Location: arch/x86/kernel/tboot.c:218
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81043fd1-ffffffff81043fdd: tboot_shutdown.cold (STB_LOCAL)
ffffffff81043c40-ffffffff81043d75: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810475e0)
Location: arch/x86/kernel/tboot.c:220
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff810475e0-ffffffff8104763a: tboot_shutdown.part.0 (STB_LOCAL)
ffffffff810477e0-ffffffff8104781d: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81046e10)
Location: arch/x86/kernel/tboot.c:221
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81046e10-ffffffff81046e6a: tboot_shutdown.part.0 (STB_LOCAL)
ffffffff81047010-ffffffff8104704d: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810487c5)
Location: arch/x86/kernel/tboot.c:229
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81bc7252-ffffffff81bc725e: tboot_shutdown.cold (STB_LOCAL)
ffffffff81048790-ffffffff810488c9: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8104f10e)
Location: arch/x86/kernel/tboot.c:229
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81c9a84a-ffffffff81c9a856: tboot_shutdown.cold (STB_LOCAL)
ffffffff8104f0d0-ffffffff8104f25c: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8105a37e)
Location: arch/x86/kernel/tboot.c:228
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_sleep
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81e49ccc-ffffffff81e49cd8: tboot_shutdown.cold (STB_LOCAL)
ffffffff8105a340-ffffffff8105a4e4: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810680f0)
Location: arch/x86/kernel/tboot.c:227
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_sleep
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff810680f0-ffffffff810682a0: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81069970)
Location: arch/x86/kernel/tboot.c:227
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_sleep
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81069970-ffffffff81069bbb: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81070b40)
Location: arch/x86/kernel/tboot.c:227
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_sleep
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81070b40-ffffffff81070b98: tboot_shutdown.part.0 (STB_LOCAL)
ffffffff81070ea0-ffffffff81071084: tboot_shutdown (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81043deb)
Location: arch/x86/kernel/tboot.c:218
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81044151-ffffffff8104415d: tboot_shutdown.cold (STB_LOCAL)
ffffffff81043dc0-ffffffff81043ef5: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103341b)
Location: arch/x86/kernel/tboot.c:218
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81033771-ffffffff8103377d: tboot_shutdown.cold (STB_LOCAL)
ffffffff810333f0-ffffffff81033520: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81043c2b)
Location: arch/x86/kernel/tboot.c:218
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81043f91-ffffffff81043f9d: tboot_shutdown.cold (STB_LOCAL)
ffffffff81043c00-ffffffff81043d35: tboot_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tboot_shutdown(u32 shutdown_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8104502b)
Location: arch/x86/kernel/tboot.c:218
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81045391-ffffffff8104539d: tboot_shutdown.cold (STB_LOCAL)
ffffffff81045000-ffffffff81045135: tboot_shutdown (STB_GLOBAL)
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
