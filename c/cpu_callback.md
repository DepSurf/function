# Function: <code>cpu_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int cpu_callback(struct notifier_block *nfb, long unsigned int action, void *hcpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810856a0)
Location: kernel/softirq.c:729
Inline: False
```
```
In mm/vmscan.c (ffffffff811a0c90)
Location: mm/vmscan.c:3578
Inline: True
```
**Symbols:**

```
ffffffff810856a0-ffffffff81085896: cpu_callback (STB_LOCAL)
ffffffff811a0c90-ffffffff811a0d5d: cpu_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int cpu_callback(struct notifier_block *nfb, long unsigned int action, void *hcpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81088780)
Location: kernel/softirq.c:729
Inline: False
```
```
In mm/vmscan.c (ffffffff811b70b0)
Location: mm/vmscan.c:3562
Inline: True
```
```
In mm/compaction.c (ffffffff811cf2e0)
Location: mm/compaction.c:2053
Inline: True
```
**Symbols:**

```
ffffffff81088780-ffffffff81088964: cpu_callback (STB_LOCAL)
ffffffff811b70b0-ffffffff811b717e: cpu_callback (STB_LOCAL)
ffffffff811cf2e0-ffffffff811cf3ae: cpu_callback (STB_LOCAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
