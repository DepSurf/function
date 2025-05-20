# Function: <code>sync_pcpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff814d2490)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff814d2490-ffffffff814d26d9: sync_pcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff815231c0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff815231c0-ffffffff81523404: sync_pcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff8154f6a0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff8154f6a0-ffffffff8154f8e4: sync_pcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff81563dd0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff81563dd0-ffffffff8156401d: sync_pcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff815c7f20)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff815c7f20-ffffffff815c816d: sync_pcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff81600790)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff81600790-ffffffff816009e0: sync_pcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff8161b860)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff8161b860-ffffffff8161bab0: sync_pcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff8164f4e0-ffffffff8164f6d6: sync_pcpu (STB_LOCAL)
ffffffff8164f7b0-ffffffff8164f7fa: sync_pcpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff81671a90-ffffffff81671c86: sync_pcpu (STB_LOCAL)
ffffffff81671d60-ffffffff81671daa: sync_pcpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff81722160-ffffffff81722351: sync_pcpu (STB_LOCAL)
ffffffff81722430-ffffffff8172247a: sync_pcpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff8173ee10-ffffffff8173f001: sync_pcpu (STB_LOCAL)
ffffffff81c05a56-ffffffff81c05aa0: sync_pcpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff81722860-ffffffff81722a51: sync_pcpu (STB_LOCAL)
ffffffff81bf7701-ffffffff81bf774b: sync_pcpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff817a16b0-ffffffff817a18a1: sync_pcpu (STB_LOCAL)
ffffffff81cf663e-ffffffff81cf6688: sync_pcpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff818db690-ffffffff818db8c7: sync_pcpu (STB_LOCAL)
ffffffff81ebe774-ffffffff81ebe7bf: sync_pcpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff81a2e790)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff81a2e790-ffffffff81a2e9db: sync_pcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff81a77f40)
Location: drivers/xen/pcpu.c:271
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff81a77f40-ffffffff81a78199: sync_pcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pcpu.c (ffffffff81aca150)
Location: drivers/xen/pcpu.c:274
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff81aca150-ffffffff81aca3d8: sync_pcpu (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff81637b50-ffffffff81637d46: sync_pcpu (STB_LOCAL)
ffffffff81637e20-ffffffff81637e6a: sync_pcpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff816658d0-ffffffff81665ac6: sync_pcpu (STB_LOCAL)
ffffffff81665ba0-ffffffff81665bea: sync_pcpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sync_pcpu(uint32_t cpu, uint32_t *max_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pcpu.c (0)
Location: drivers/xen/pcpu.c:269
Inline: False
Direct callers:
  - drivers/xen/pcpu.c:xen_sync_pcpus
```
**Symbols:**

```
ffffffff8167fe80-ffffffff81680076: sync_pcpu (STB_LOCAL)
ffffffff81680150-ffffffff8168019a: sync_pcpu.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
