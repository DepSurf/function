# Function: <code>vcpu_online</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/cpu_hotplug.c (ffffffff814c4420)
Location: drivers/xen/cpu_hotplug.c:32
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff814c4420-ffffffff814c452a: vcpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/cpu_hotplug.c (ffffffff81514bc0)
Location: drivers/xen/cpu_hotplug.c:32
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81514bc0-ffffffff81514cb4: vcpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/cpu_hotplug.c (ffffffff81541050)
Location: drivers/xen/cpu_hotplug.c:32
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81541050-ffffffff81541144: vcpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/cpu_hotplug.c (ffffffff81554ee0)
Location: drivers/xen/cpu_hotplug.c:32
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81554ee0-ffffffff81554fd4: vcpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/cpu_hotplug.c (ffffffff815b8a50)
Location: drivers/xen/cpu_hotplug.c:33
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff815b8a50-ffffffff815b8b44: vcpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:33
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff815f1000-ffffffff815f10d6: vcpu_online (STB_LOCAL)
ffffffff815f122e-ffffffff815f125b: vcpu_online.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff8160bc20-ffffffff8160bcf6: vcpu_online (STB_LOCAL)
ffffffff8160be6e-ffffffff8160be9b: vcpu_online.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff8163faa0-ffffffff8163fb7d: vcpu_online (STB_LOCAL)
ffffffff8163fcef-ffffffff8163fd00: vcpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81662060-ffffffff8166213d: vcpu_online (STB_LOCAL)
ffffffff816622af-ffffffff816622c0: vcpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81711530-ffffffff8171160d: vcpu_online (STB_LOCAL)
ffffffff817117be-ffffffff817117cf: vcpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff8172e260-ffffffff8172e33d: vcpu_online (STB_LOCAL)
ffffffff81c04a44-ffffffff81c04a55: vcpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81711f30-ffffffff8171200d: vcpu_online (STB_LOCAL)
ffffffff81bf662d-ffffffff81bf663e: vcpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff8178e9a0-ffffffff8178ea7d: vcpu_online (STB_LOCAL)
ffffffff81cf527c-ffffffff81cf528d: vcpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff818c6980-ffffffff818c6a81: vcpu_online (STB_LOCAL)
ffffffff81ebd3d0-ffffffff81ebd3e1: vcpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/cpu_hotplug.c (ffffffff81a17300)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81a17300-ffffffff81a17407: vcpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/cpu_hotplug.c (ffffffff81a60390)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81a60390-ffffffff81a60497: vcpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/cpu_hotplug.c (ffffffff81ab2bd0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81ab2bd0-ffffffff81ab2cd7: vcpu_online (STB_LOCAL)
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
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/cpu_hotplug.c (ffff80001082b460)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffff80001082b460-ffff80001082b58c: vcpu_online (STB_LOCAL)
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
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81627ed0-ffffffff81627fad: vcpu_online (STB_LOCAL)
ffffffff8162811f-ffffffff81628130: vcpu_online.cold (STB_LOCAL)
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
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81655ea0-ffffffff81655f7d: vcpu_online (STB_LOCAL)
ffffffff816560ef-ffffffff81656100: vcpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vcpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/cpu_hotplug.c (0)
Location: drivers/xen/cpu_hotplug.c:34
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81670480-ffffffff8167055d: vcpu_online (STB_LOCAL)
ffffffff816706cf-ffffffff816706e0: vcpu_online.cold (STB_LOCAL)
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
