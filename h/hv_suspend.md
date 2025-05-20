# Function: <code>hv_suspend</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hv_suspend();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81030110)
Location: arch/x86/hyperv/hv_init.c:267
Inline: False
```
**Symbols:**

```
ffffffff81030110-ffffffff81030166: hv_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hv_suspend();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81030d40)
Location: arch/x86/hyperv/hv_init.c:270
Inline: False
```
**Symbols:**

```
ffffffff81030d40-ffffffff81030d96: hv_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hv_suspend();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81031890)
Location: arch/x86/hyperv/hv_init.c:271
Inline: False
```
**Symbols:**

```
ffffffff81031890-ffffffff810318f5: hv_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hv_suspend();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:253
Inline: False
```
**Symbols:**

```
ffffffff81036800-ffffffff81036872: hv_suspend (STB_LOCAL)
ffffffff81c97dfc-ffffffff81c97e10: hv_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hv_suspend();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:293
Inline: False
```
**Symbols:**

```
ffffffff8103c7c0-ffffffff8103c848: hv_suspend (STB_LOCAL)
ffffffff81e4723d-ffffffff81e47251: hv_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hv_suspend();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:283
Inline: False
```
**Symbols:**

```
ffffffff81045620-ffffffff810456a8: hv_suspend (STB_LOCAL)
ffffffff82051eea-ffffffff82051efe: hv_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hv_suspend();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:286
Inline: False
```
**Symbols:**

```
ffffffff81045760-ffffffff810457e8: hv_suspend (STB_LOCAL)
ffffffff820d035f-ffffffff820d0373: hv_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hv_suspend();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:320
Inline: False
```
**Symbols:**

```
ffffffff8104be30-ffffffff8104beb8: hv_suspend (STB_LOCAL)
ffffffff821aacf5-ffffffff821aad09: hv_suspend.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
