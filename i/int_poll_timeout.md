# Function: <code>int_poll_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void int_poll_timeout(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814508c0)
Location: drivers/pci/hotplug/pciehp_hpc.c:53
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff814508c0-ffffffff81450944: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void int_poll_timeout(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149d0d0)
Location: drivers/pci/hotplug/pciehp_hpc.c:53
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff8149d0d0-ffffffff8149d154: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void int_poll_timeout(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bec50)
Location: drivers/pci/hotplug/pciehp_hpc.c:53
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff814bec50-ffffffff814becd7: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void int_poll_timeout(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c93e0)
Location: drivers/pci/hotplug/pciehp_hpc.c:53
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff814c93e0-ffffffff814c9467: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815099b0)
Location: drivers/pci/hotplug/pciehp_hpc.c:53
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff815099b0-ffffffff81509a1e: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153a9a0)
Location: drivers/pci/hotplug/pciehp_hpc.c:38
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153e550)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff8153a9a0-ffffffff8153aa0e: int_poll_timeout (STB_LOCAL)
ffffffff8153e550-ffffffff8153e5b6: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81555920)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff81555920-ffffffff81555986: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81585920)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff81585920-ffffffff81585989: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a7300)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff815a7300-ffffffff815a7369: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81650010)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff81650010-ffffffff8165007b: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff816734b0)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff816734b0-ffffffff8167351b: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff816559d0)
Location: drivers/pci/hotplug/shpchp_hpc.c:213
Inline: False
```
**Symbols:**

```
ffffffff816559d0-ffffffff81655a3b: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff816c7850)
Location: drivers/pci/hotplug/shpchp_hpc.c:213
Inline: False
```
**Symbols:**

```
ffffffff816c7850-ffffffff816c78bb: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff817ed8a0)
Location: drivers/pci/hotplug/shpchp_hpc.c:213
Inline: False
```
**Symbols:**

```
ffffffff817ed8a0-ffffffff817ed90e: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81914c70)
Location: drivers/pci/hotplug/shpchp_hpc.c:213
Inline: False
```
**Symbols:**

```
ffffffff81914c70-ffffffff81914cde: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81958290)
Location: drivers/pci/hotplug/shpchp_hpc.c:213
Inline: False
```
**Symbols:**

```
ffffffff81958290-ffffffff819582fe: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a1800)
Location: drivers/pci/hotplug/shpchp_hpc.c:213
Inline: False
```
**Symbols:**

```
ffffffff819a1800-ffffffff819a186e: int_poll_timeout (STB_LOCAL)
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
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710a40)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffff800010710a40-ffff800010710ac4: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dc350)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffe0004dc350-ffffffe0004dc3c2: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159ab10)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff8159ab10-ffffffff8159ab79: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81589ca0)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff81589ca0-ffffffff81589d09: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159b050)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff8159b050-ffffffff8159b0b9: int_poll_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void int_poll_timeout(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b5490)
Location: drivers/pci/hotplug/shpchp_hpc.c:218
Inline: False
```
**Symbols:**

```
ffffffff815b5490-ffffffff815b54f9: int_poll_timeout (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct timer_list *t</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int data</code>
</li>
</ul>
</details>
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
