# Function: <code>kvm_cs_enable</code>

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
int kvm_cs_enable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8107f5e0)
Location: arch/x86/kernel/kvmclock.c:162
Inline: False
```
**Symbols:**

```
ffffffff8107f5e0-ffffffff8107f5f2: kvm_cs_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kvm_cs_enable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8107f240)
Location: arch/x86/kernel/kvmclock.c:161
Inline: False
```
**Symbols:**

```
ffffffff8107f240-ffffffff8107f252: kvm_cs_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kvm_cs_enable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810803a0)
Location: arch/x86/kernel/kvmclock.c:160
Inline: False
```
**Symbols:**

```
ffffffff810803a0-ffffffff810803b2: kvm_cs_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kvm_cs_enable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8108f230)
Location: arch/x86/kernel/kvmclock.c:151
Inline: False
```
**Symbols:**

```
ffffffff8108f230-ffffffff8108f242: kvm_cs_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kvm_cs_enable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8109ff20)
Location: arch/x86/kernel/kvmclock.c:151
Inline: False
```
**Symbols:**

```
ffffffff8109ff20-ffffffff8109ff36: kvm_cs_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kvm_cs_enable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810b7930)
Location: arch/x86/kernel/kvmclock.c:151
Inline: False
```
**Symbols:**

```
ffffffff810b7930-ffffffff810b7946: kvm_cs_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kvm_cs_enable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810bab20)
Location: arch/x86/kernel/kvmclock.c:151
Inline: False
```
**Symbols:**

```
ffffffff810bab20-ffffffff810bab36: kvm_cs_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kvm_cs_enable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810c1f60)
Location: arch/x86/kernel/kvmclock.c:151
Inline: False
```
**Symbols:**

```
ffffffff810c1f60-ffffffff810c1f76: kvm_cs_enable (STB_LOCAL)
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
