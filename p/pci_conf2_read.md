# Function: <code>pci_conf2_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff816f6c30)
Location: arch/x86/pci/direct.c:94
Inline: False
```
**Symbols:**

```
ffffffff816f6c30-ffffffff816f6d9c: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8175b8b0)
Location: arch/x86/pci/direct.c:94
Inline: False
```
**Symbols:**

```
ffffffff8175b8b0-ffffffff8175ba1e: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81787e20)
Location: arch/x86/pci/direct.c:94
Inline: False
```
**Symbols:**

```
ffffffff81787e20-ffffffff81787f8e: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff817a6f30)
Location: arch/x86/pci/direct.c:94
Inline: False
```
**Symbols:**

```
ffffffff817a6f30-ffffffff817a7078: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8181e190)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff8181e190-ffffffff8181e2d8: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff818682c0)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff818682c0-ffffffff81868402: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81888340)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff81888340-ffffffff81888482: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (0)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff818d2d80-ffffffff818d2eb1: pci_conf2_read (STB_LOCAL)
ffffffff818d2eed-ffffffff818d2f0f: pci_conf2_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81905130)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff81905130-ffffffff81905268: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81bb56f0)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff81bb56f0-ffffffff81bb582a: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81bca8d0)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff81bca8d0-ffffffff81bcaa0a: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81bbe220)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff81bbe220-ffffffff81bbe348: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81c8e160)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff81c8e160-ffffffff81c8e288: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81e3d140)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff81e3d140-ffffffff81e3d267: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff82016470)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff82016470-ffffffff82016597: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff82096820)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff82096820-ffffffff82096947: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8216dd30)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff8216dd30-ffffffff8216de57: pci_conf2_read (STB_LOCAL)
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
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff818a4560)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff818a4560-ffffffff818a4698: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8185fcd0)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff8185fcd0-ffffffff8185fe08: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff818f5b50)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff818f5b50-ffffffff818f5c88: pci_conf2_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_conf2_read(unsigned int seg, unsigned int bus, unsigned int devfn, int reg, int len, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81916c40)
Location: arch/x86/pci/direct.c:95
Inline: False
```
**Symbols:**

```
ffffffff81916c40-ffffffff81916d78: pci_conf2_read (STB_LOCAL)
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
