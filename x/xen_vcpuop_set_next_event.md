# Function: <code>xen_vcpuop_set_next_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81023800)
Location: arch/x86/xen/time.c:336
Inline: True
```
**Symbols:**

```
ffffffff81023800-ffffffff81023896: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81022b40)
Location: arch/x86/xen/time.c:246
Inline: True
```
**Symbols:**

```
ffffffff81022b40-ffffffff81022be5: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81023290)
Location: arch/x86/xen/time.c:246
Inline: True
```
**Symbols:**

```
ffffffff81023290-ffffffff81023335: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101af70)
Location: arch/x86/xen/time.c:248
Inline: True
```
**Symbols:**

```
ffffffff8101af70-ffffffff8101b006: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101b870)
Location: arch/x86/xen/time.c:249
Inline: True
```
**Symbols:**

```
ffffffff8101b870-ffffffff8101b906: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101c160)
Location: arch/x86/xen/time.c:249
Inline: False
```
**Symbols:**

```
ffffffff8101c160-ffffffff8101c1f6: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101bac0)
Location: arch/x86/xen/time.c:256
Inline: False
```
**Symbols:**

```
ffffffff8101bac0-ffffffff8101bb56: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:256
Inline: False
```
**Symbols:**

```
ffffffff8101d600-ffffffff8101d697: xen_vcpuop_set_next_event (STB_LOCAL)
ffffffff8101dbb9-ffffffff8101dbcc: xen_vcpuop_set_next_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e290)
Location: arch/x86/xen/time.c:256
Inline: True
```
**Symbols:**

```
ffffffff8101e290-ffffffff8101e327: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81020710)
Location: arch/x86/xen/time.c:263
Inline: False
```
**Symbols:**

```
ffffffff81020710-ffffffff810207a7: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81021150)
Location: arch/x86/xen/time.c:264
Inline: False
```
**Symbols:**

```
ffffffff81021150-ffffffff810211e7: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810234f0)
Location: arch/x86/xen/time.c:264
Inline: False
```
**Symbols:**

```
ffffffff810234f0-ffffffff81023587: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810276f0)
Location: arch/x86/xen/time.c:264
Inline: False
```
**Symbols:**

```
ffffffff810276f0-ffffffff810277a5: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8102ba50)
Location: arch/x86/xen/time.c:264
Inline: False
```
**Symbols:**

```
ffffffff8102ba50-ffffffff8102bb43: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810327c0)
Location: arch/x86/xen/time.c:264
Inline: False
```
**Symbols:**

```
ffffffff810327c0-ffffffff810328b3: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81032760)
Location: arch/x86/xen/time.c:272
Inline: False
```
**Symbols:**

```
ffffffff81032760-ffffffff81032853: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81038a50)
Location: arch/x86/xen/time.c:272
Inline: False
```
**Symbols:**

```
ffffffff81038a50-ffffffff81038b43: xen_vcpuop_set_next_event (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e2a0)
Location: arch/x86/xen/time.c:256
Inline: True
```
**Symbols:**

```
ffffffff8101e2a0-ffffffff8101e337: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e250)
Location: arch/x86/xen/time.c:256
Inline: True
```
**Symbols:**

```
ffffffff8101e250-ffffffff8101e2e7: xen_vcpuop_set_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xen_vcpuop_set_next_event(long unsigned int delta, struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e4d0)
Location: arch/x86/xen/time.c:256
Inline: True
```
**Symbols:**

```
ffffffff8101e4d0-ffffffff8101e55b: xen_vcpuop_set_next_event (STB_LOCAL)
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
