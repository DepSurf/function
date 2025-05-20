# Function: <code>poll_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144d6f0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:544
Inline: False
```
**Symbols:**

```
ffffffff8144d6f0-ffffffff8144d795: poll_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81499e30)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:544
Inline: False
```
**Symbols:**

```
ffffffff81499e30-ffffffff81499ed5: poll_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bba20)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:544
Inline: False
```
**Symbols:**

```
ffffffff814bba20-ffffffff814bbac0: poll_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c6220)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:545
Inline: False
```
**Symbols:**

```
ffffffff814c6220-ffffffff814c62cc: poll_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815067d0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:545
Inline: False
```
**Symbols:**

```
ffffffff815067d0-ffffffff8150687f: poll_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:531
Inline: True
```
**Symbols:**

```
ffffffff81537640-ffffffff815376d4: poll_thread (STB_LOCAL)
ffffffff8153805c-ffffffff8153807b: poll_thread.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154ed98)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
ffffffff8154ed20-ffffffff8154edb4: poll_thread (STB_LOCAL)
ffffffff8154f442-ffffffff8154f461: poll_thread.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157eccc)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
ffffffff8157ec50-ffffffff8157ece9: poll_thread (STB_LOCAL)
ffffffff8157f32a-ffffffff8157f349: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815a070c)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
ffffffff815a0690-ffffffff815a0729: poll_thread (STB_LOCAL)
ffffffff815a0d6a-ffffffff815a0d89: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: False
```
**Symbols:**

```
ffffffff81648f10-ffffffff81648faf: poll_thread (STB_LOCAL)
ffffffff8164970b-ffffffff8164972a: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: False
```
**Symbols:**

```
ffffffff8166dfc0-ffffffff8166e063: poll_thread (STB_LOCAL)
ffffffff81bfba45-ffffffff81bfba64: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: False
```
**Symbols:**

```
ffffffff81650510-ffffffff816505b3: poll_thread (STB_LOCAL)
ffffffff81bed8d1-ffffffff81bed8f0: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: False
```
**Symbols:**

```
ffffffff816c2250-ffffffff816c22f3: poll_thread (STB_LOCAL)
ffffffff81ce85fb-ffffffff81ce861a: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: False
```
**Symbols:**

```
ffffffff817e7b80-ffffffff817e7c2d: poll_thread (STB_LOCAL)
ffffffff81eaf67a-ffffffff81eaf699: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190d220)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: False
```
**Symbols:**

```
ffffffff8190d220-ffffffff8190d2ef: poll_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff819508a0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: False
```
**Symbols:**

```
ffffffff819508a0-ffffffff8195096f: poll_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999d00)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: False
```
**Symbols:**

```
ffffffff81999d00-ffffffff81999dcf: poll_thread (STB_LOCAL)
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
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708f30)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
ffff800010708f30-ffff800010709010: poll_thread (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000881fc0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
c000000000881fc0-c00000000088211c: poll_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d698e)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
ffffffe0004d698e-ffffffe0004d6a68: poll_thread (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593f1c)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
ffffffff81593ea0-ffffffff81593f39: poll_thread (STB_LOCAL)
ffffffff8159457a-ffffffff81594599: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815830ac)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
ffffffff81583030-ffffffff815830c9: poll_thread (STB_LOCAL)
ffffffff8158370a-ffffffff81583729: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8159445c)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
ffffffff815943e0-ffffffff81594479: poll_thread (STB_LOCAL)
ffffffff81594aba-ffffffff81594ad9: poll_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int poll_thread(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815ae8dc)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:467
Inline: True
```
**Symbols:**

```
ffffffff815ae860-ffffffff815ae8f9: poll_thread (STB_LOCAL)
ffffffff815aef3a-ffffffff815aef59: poll_thread.cold (STB_LOCAL)
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
