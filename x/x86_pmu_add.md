# Function: <code>x86_pmu_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005330)
Location: arch/x86/events/core.c:1155
Inline: False
```
**Symbols:**

```
ffffffff81005330-ffffffff81005424: x86_pmu_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005560)
Location: arch/x86/events/core.c:1182
Inline: False
```
**Symbols:**

```
ffffffff81005560-ffffffff81005654: x86_pmu_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005580)
Location: arch/x86/events/core.c:1191
Inline: False
```
**Symbols:**

```
ffffffff81005580-ffffffff81005688: x86_pmu_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810053a0)
Location: arch/x86/events/core.c:1192
Inline: False
```
**Symbols:**

```
ffffffff810053a0-ffffffff810054c1: x86_pmu_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005670)
Location: arch/x86/events/core.c:1198
Inline: False
```
**Symbols:**

```
ffffffff81005670-ffffffff8100579a: x86_pmu_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1201
Inline: False
```
**Symbols:**

```
ffffffff81005e10-ffffffff81005f2d: x86_pmu_add (STB_LOCAL)
ffffffff810083b1-ffffffff810083bd: x86_pmu_add.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1202
Inline: False
```
**Symbols:**

```
ffffffff81005c00-ffffffff81005d1d: x86_pmu_add (STB_LOCAL)
ffffffff81008285-ffffffff81008291: x86_pmu_add.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1241
Inline: False
```
**Symbols:**

```
ffffffff81005b20-ffffffff81005c3d: x86_pmu_add (STB_LOCAL)
ffffffff81008485-ffffffff81008491: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1311
Inline: False
```
**Symbols:**

```
ffffffff81005ad0-ffffffff81005bed: x86_pmu_add (STB_LOCAL)
ffffffff81008785-ffffffff81008791: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1312
Inline: False
```
**Symbols:**

```
ffffffff81006a20-ffffffff81006b3d: x86_pmu_add (STB_LOCAL)
ffffffff81009747-ffffffff81009753: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1391
Inline: False
```
**Symbols:**

```
ffffffff810064f0-ffffffff810065fc: x86_pmu_add (STB_LOCAL)
ffffffff81bd1f37-ffffffff81bd1f43: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1444
Inline: False
```
**Symbols:**

```
ffffffff81006810-ffffffff8100691c: x86_pmu_add (STB_LOCAL)
ffffffff81bc3e63-ffffffff81bc3e6f: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1442
Inline: False
```
**Symbols:**

```
ffffffff81006ef0-ffffffff81006ffc: x86_pmu_add (STB_LOCAL)
ffffffff81c94f50-ffffffff81c94f5c: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1450
Inline: False
```
**Symbols:**

```
ffffffff810063a0-ffffffff810064d6: x86_pmu_add (STB_LOCAL)
ffffffff81e4424a-ffffffff81e44256: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007930)
Location: arch/x86/events/core.c:1439
Inline: False
```
**Symbols:**

```
ffffffff81007930-ffffffff81007a6e: x86_pmu_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007090)
Location: arch/x86/events/core.c:1439
Inline: False
```
**Symbols:**

```
ffffffff81007090-ffffffff810071ce: x86_pmu_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100c7c0)
Location: arch/x86/events/core.c:1437
Inline: False
```
**Symbols:**

```
ffffffff8100c7c0-ffffffff8100c8fe: x86_pmu_add (STB_LOCAL)
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
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1311
Inline: False
```
**Symbols:**

```
ffffffff81005ad0-ffffffff81005bed: x86_pmu_add (STB_LOCAL)
ffffffff81008785-ffffffff81008791: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1311
Inline: False
```
**Symbols:**

```
ffffffff810041f0-ffffffff8100430d: x86_pmu_add (STB_LOCAL)
ffffffff81006fa4-ffffffff81006fb0: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1311
Inline: False
```
**Symbols:**

```
ffffffff81005a90-ffffffff81005bad: x86_pmu_add (STB_LOCAL)
ffffffff81008745-ffffffff81008751: x86_pmu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int x86_pmu_add(struct perf_event *event, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:1311
Inline: False
```
**Symbols:**

```
ffffffff81005bf0-ffffffff81005d0d: x86_pmu_add (STB_LOCAL)
ffffffff810088a5-ffffffff810088b1: x86_pmu_add.cold (STB_LOCAL)
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
