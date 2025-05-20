# Function: <code>ts_dmi_notifier_call</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81877eb0)
Location: drivers/platform/x86/touchscreen_dmi.c:805
Inline: True
```
**Symbols:**

```
ffffffff81877eb0-ffffffff81877f31: ts_dmi_notifier_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff818bcb3e)
Location: drivers/platform/x86/touchscreen_dmi.c:957
Inline: True
```
**Symbols:**

```
ffffffff818bcb30-ffffffff818bcba6: ts_dmi_notifier_call (STB_LOCAL)
ffffffff818bcba6-ffffffff818bcbbc: ts_dmi_notifier_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff818ef65e)
Location: drivers/platform/x86/touchscreen_dmi.c:1015
Inline: True
```
**Symbols:**

```
ffffffff818ef650-ffffffff818ef6c6: ts_dmi_notifier_call (STB_LOCAL)
ffffffff818ef6c6-ffffffff818ef6dc: ts_dmi_notifier_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff819c33fe)
Location: drivers/platform/x86/touchscreen_dmi.c:1244
Inline: True
```
**Symbols:**

```
ffffffff819c33f0-ffffffff819c3466: ts_dmi_notifier_call (STB_LOCAL)
ffffffff819c3466-ffffffff819c347c: ts_dmi_notifier_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff819c37de)
Location: drivers/platform/x86/touchscreen_dmi.c:1337
Inline: True
```
**Symbols:**

```
ffffffff819c37d0-ffffffff819c3846: ts_dmi_notifier_call (STB_LOCAL)
ffffffff81c2d3ec-ffffffff81c2d402: ts_dmi_notifier_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff819a7d1e)
Location: drivers/platform/x86/touchscreen_dmi.c:1527
Inline: True
```
**Symbols:**

```
ffffffff819a7d10-ffffffff819a7d88: ts_dmi_notifier_call (STB_LOCAL)
ffffffff81c1f66a-ffffffff81c1f680: ts_dmi_notifier_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81a5754e)
Location: drivers/platform/x86/touchscreen_dmi.c:1597
Inline: True
```
**Symbols:**

```
ffffffff81a57540-ffffffff81a575b8: ts_dmi_notifier_call (STB_LOCAL)
ffffffff81d30fe2-ffffffff81d30ff8: ts_dmi_notifier_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81bc7008)
Location: drivers/platform/x86/touchscreen_dmi.c:1628
Inline: True
```
**Symbols:**

```
ffffffff81bc6ff0-ffffffff81bc707b: ts_dmi_notifier_call (STB_LOCAL)
ffffffff81efd416-ffffffff81efd42c: ts_dmi_notifier_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81d6f830)
Location: drivers/platform/x86/touchscreen_dmi.c:1687
Inline: True
```
**Symbols:**

```
ffffffff81d6f830-ffffffff81d6f8c8: ts_dmi_notifier_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81ddd4f0)
Location: drivers/platform/x86/touchscreen_dmi.c:1751
Inline: True
```
**Symbols:**

```
ffffffff81ddd4f0-ffffffff81ddd587: ts_dmi_notifier_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81e93200)
Location: drivers/platform/x86/touchscreen_dmi.c:1826
Inline: True
```
**Symbols:**

```
ffffffff81e93200-ffffffff81e932a2: ts_dmi_notifier_call (STB_LOCAL)
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
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff818e448e)
Location: drivers/platform/x86/touchscreen_dmi.c:1015
Inline: True
```
**Symbols:**

```
ffffffff818e4480-ffffffff818e44f6: ts_dmi_notifier_call (STB_LOCAL)
ffffffff818e44f6-ffffffff818e450c: ts_dmi_notifier_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ts_dmi_notifier_call(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff819010ee)
Location: drivers/platform/x86/touchscreen_dmi.c:1015
Inline: True
```
**Symbols:**

```
ffffffff819010e0-ffffffff81901156: ts_dmi_notifier_call (STB_LOCAL)
ffffffff81901156-ffffffff8190116c: ts_dmi_notifier_call.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
