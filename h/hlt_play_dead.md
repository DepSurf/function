# Function: <code>hlt_play_dead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105288e)
Location: arch/x86/kernel/smpboot.c:1627
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81052890)
Location: arch/x86/kernel/smpboot.c:1654
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81052890-ffffffff810528c8: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810551a0)
Location: arch/x86/kernel/smpboot.c:1681
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff810551a0-ffffffff810551d8: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054aa0)
Location: arch/x86/kernel/smpboot.c:1686
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81054aa0-ffffffff81054ad8: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81058860)
Location: arch/x86/kernel/smpboot.c:1599
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81058860-ffffffff81058898: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105b4d0)
Location: arch/x86/kernel/smpboot.c:1657
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8105b4d0-ffffffff8105b508: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81061150)
Location: arch/x86/kernel/smpboot.c:1659
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81061150-ffffffff81061188: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064800)
Location: arch/x86/kernel/smpboot.c:1724
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81064800-ffffffff81064846: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064e80)
Location: arch/x86/kernel/smpboot.c:1724
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81064e80-ffffffff81064ec6: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106b5b0)
Location: arch/x86/kernel/smpboot.c:1751
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8106b5b0-ffffffff8106b5f4: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106d250)
Location: arch/x86/kernel/smpboot.c:1745
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8106d250-ffffffff8106d294: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106dcc0)
Location: arch/x86/kernel/smpboot.c:1747
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8106dcc0-ffffffff8106dd04: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810794d0)
Location: arch/x86/kernel/smpboot.c:1754
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff810794d0-ffffffff81079511: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81088360)
Location: arch/x86/kernel/smpboot.c:1819
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81088360-ffffffff810883a1: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109be10)
Location: arch/x86/kernel/smpboot.c:1819
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8109be10-ffffffff8109be51: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109ee80)
Location: arch/x86/kernel/smpboot.c:1737
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8109ee80-ffffffff8109eea6: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a62b0)
Location: arch/x86/kernel/smpboot.c:1601
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff810a62b0-ffffffff810a62d6: hlt_play_dead (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064970)
Location: arch/x86/kernel/smpboot.c:1724
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81064970-ffffffff810649b6: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054c60)
Location: arch/x86/kernel/smpboot.c:1724
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81054c60-ffffffff81054c9f: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064e20)
Location: arch/x86/kernel/smpboot.c:1724
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81064e20-ffffffff81064e66: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hlt_play_dead();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81066400)
Location: arch/x86/kernel/smpboot.c:1724
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81066400-ffffffff81066446: hlt_play_dead (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
