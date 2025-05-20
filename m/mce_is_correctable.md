# Function: <code>mce_is_correctable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c3b2)
Location: arch/x86/kernel/cpu/mcheck/mce.c:537
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81048b20)
Location: arch/x86/kernel/cpu/mce/core.c:536
Inline: True
```
**Symbols:**

```
ffffffff81048b20-ffffffff81048b61: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104bbe0)
Location: arch/x86/kernel/cpu/mce/core.c:536
Inline: True
```
**Symbols:**

```
ffffffff8104bbe0-ffffffff8104bc1d: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c5a0)
Location: arch/x86/kernel/cpu/mce/core.c:536
Inline: True
```
**Symbols:**

```
ffffffff8104c5a0-ffffffff8104c5dd: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050ea0)
Location: arch/x86/kernel/cpu/mce/core.c:531
Inline: False
```
**Symbols:**

```
ffffffff81050ea0-ffffffff81050edd: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050070)
Location: arch/x86/kernel/cpu/mce/core.c:597
Inline: False
```
**Symbols:**

```
ffffffff81050070-ffffffff810500ad: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051be0)
Location: arch/x86/kernel/cpu/mce/core.c:597
Inline: False
```
**Symbols:**

```
ffffffff81051be0-ffffffff81051c1d: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a170)
Location: arch/x86/kernel/cpu/mce/core.c:606
Inline: False
```
**Symbols:**

```
ffffffff8105a170-ffffffff8105a1ad: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81066910)
Location: arch/x86/kernel/cpu/mce/core.c:531
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81066910-ffffffff8106694c: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81075c20)
Location: arch/x86/kernel/cpu/mce/core.c:531
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81075c20-ffffffff81075c5c: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077da0)
Location: arch/x86/kernel/cpu/mce/core.c:525
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81077da0-ffffffff81077ddc: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107f280)
Location: arch/x86/kernel/cpu/mce/core.c:546
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff8107f280-ffffffff8107f2bc: mce_is_correctable (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c710)
Location: arch/x86/kernel/cpu/mce/core.c:536
Inline: True
```
**Symbols:**

```
ffffffff8104c710-ffffffff8104c74d: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103bb70)
Location: arch/x86/kernel/cpu/mce/core.c:536
Inline: True
```
**Symbols:**

```
ffffffff8103bb70-ffffffff8103bbad: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c550)
Location: arch/x86/kernel/cpu/mce/core.c:536
Inline: True
```
**Symbols:**

```
ffffffff8104c550-ffffffff8104c58d: mce_is_correctable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool mce_is_correctable(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d960)
Location: arch/x86/kernel/cpu/mce/core.c:536
Inline: True
```
**Symbols:**

```
ffffffff8104d960-ffffffff8104d99d: mce_is_correctable (STB_GLOBAL)
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
