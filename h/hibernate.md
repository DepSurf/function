# Function: <code>hibernate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810cfe70)
Location: kernel/power/hibernate.c:648
Inline: False
Direct callers:
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810cfe70-ffffffff810d006e: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d4940)
Location: kernel/power/hibernate.c:681
Inline: False
Direct callers:
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810d4940-ffffffff810d4be2: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810db4f0)
Location: kernel/power/hibernate.c:683
Inline: False
Direct callers:
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810db4f0-ffffffff810db792: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810da5e0)
Location: kernel/power/hibernate.c:678
Inline: False
Direct callers:
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810da5e0-ffffffff810da8ea: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810e2790)
Location: kernel/power/hibernate.c:678
Inline: False
Direct callers:
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810e2790-ffffffff810e2a68: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:685
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810eae4d-ffffffff810eb038: hibernate.cold.9 (STB_LOCAL)
ffffffff810eab00-ffffffff810eabc5: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:687
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810f6480-ffffffff810f666b: hibernate.cold.11 (STB_LOCAL)
ffffffff810f6130-ffffffff810f61f5: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:694
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810fea26-ffffffff810fec0d: hibernate.cold (STB_LOCAL)
ffffffff810fe6d0-ffffffff810fe79b: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:695
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff8110ae72-ffffffff8110b059: hibernate.cold (STB_LOCAL)
ffffffff8110ab20-ffffffff8110abfa: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:707
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81115b4f-ffffffff81115cd8: hibernate.cold (STB_LOCAL)
ffffffff81115740-ffffffff811157d9: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:707
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81bdf3d3-ffffffff81bdf553: hibernate.cold (STB_LOCAL)
ffffffff81112090-ffffffff811120fb: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:707
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81bd148a-ffffffff81bd1685: hibernate.cold (STB_LOCAL)
ffffffff81112ab0-ffffffff81112b1b: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:710
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81ca9ff3-ffffffff81caa20e: hibernate.cold (STB_LOCAL)
ffffffff81132af0-ffffffff81132b64: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:713
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81e5a1f3-ffffffff81e5a549: hibernate.cold (STB_LOCAL)
ffffffff81154a70-ffffffff81154b1c: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:717
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff82058548-ffffffff820585af: hibernate.cold (STB_LOCAL)
ffffffff81184580-ffffffff81184978: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:718
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff820d6d49-ffffffff820d6d5e: hibernate.cold (STB_LOCAL)
ffffffff81195310-ffffffff811956d1: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:724
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff821b1fdf-ffffffff821b1ff4: hibernate.cold (STB_LOCAL)
ffffffff811a3cf0-ffffffff811a40aa: hibernate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (0)
Location: include/linux/suspend.h:462
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (c03bd2c4)
Location: kernel/power/hibernate.c:695
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
c03bd2c4-c03bd61c: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (0)
Location: include/linux/suspend.h:462
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (0)
Location: include/linux/suspend.h:462
Inline: True
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
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:695
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff811030d2-ffffffff81103276: hibernate.cold (STB_LOCAL)
ffffffff81102d80-ffffffff81102e5a: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:695
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810f4332-ffffffff810f4519: hibernate.cold (STB_LOCAL)
ffffffff810f3fe0-ffffffff810f40ba: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:695
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81101342-ffffffff81101529: hibernate.cold (STB_LOCAL)
ffffffff81100ff0-ffffffff811010ca: hibernate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hibernate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:695
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff8110c712-ffffffff8110c8f9: hibernate.cold (STB_LOCAL)
ffffffff8110c3c0-ffffffff8110c49a: hibernate (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
