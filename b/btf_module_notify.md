# Function: <code>btf_module_notify</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int btf_module_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81229590)
Location: kernel/bpf/btf.c:5780
Inline: True
```
**Symbols:**

```
ffffffff81229350-ffffffff81229586: btf_module_notify.part.0 (STB_LOCAL)
ffffffff81be6580-ffffffff81be65d6: btf_module_notify.part.0.cold (STB_LOCAL)
ffffffff81229590-ffffffff812295c0: btf_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int btf_module_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122de30)
Location: kernel/bpf/btf.c:5978
Inline: True
```
**Symbols:**

```
ffffffff8122dbf0-ffffffff8122de26: btf_module_notify.part.0 (STB_LOCAL)
ffffffff81bd8280-ffffffff81bd82d6: btf_module_notify.part.0.cold (STB_LOCAL)
ffffffff8122de30-ffffffff8122de60: btf_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int btf_module_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81266a30)
Location: kernel/bpf/btf.c:6031
Inline: True
```
**Symbols:**

```
ffffffff812667f0-ffffffff81266a26: btf_module_notify.part.0 (STB_LOCAL)
ffffffff81cb944b-ffffffff81cb94a1: btf_module_notify.part.0.cold (STB_LOCAL)
ffffffff81266a30-ffffffff81266a60: btf_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int btf_module_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6771
Inline: False
```
**Symbols:**

```
ffffffff812b31f0-ffffffff812b3491: btf_module_notify (STB_LOCAL)
ffffffff81e6a744-ffffffff81e6a78d: btf_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_module_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81313640)
Location: kernel/bpf/btf.c:7250
Inline: False
```
**Symbols:**

```
ffffffff81313640-ffffffff81313923: btf_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_module_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81343310)
Location: kernel/bpf/btf.c:7349
Inline: False
```
**Symbols:**

```
ffffffff81343310-ffffffff813435e0: btf_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_module_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81369560)
Location: kernel/bpf/btf.c:7413
Inline: False
```
**Symbols:**

```
ffffffff81369560-ffffffff8136988e: btf_module_notify (STB_LOCAL)
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
