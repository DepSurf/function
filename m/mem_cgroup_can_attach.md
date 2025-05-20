# Function: <code>mem_cgroup_can_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fc0c0)
Location: mm/memcontrol.c:4814
Inline: False
```
**Symbols:**

```
ffffffff811fc0c0-ffffffff811fc296: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81220130)
Location: mm/memcontrol.c:4791
Inline: True
```
**Symbols:**

```
ffffffff81220130-ffffffff81220300: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812327c0)
Location: mm/memcontrol.c:4775
Inline: True
```
**Symbols:**

```
ffffffff812327c0-ffffffff8123298f: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123dc00)
Location: mm/memcontrol.c:4800
Inline: True
```
**Symbols:**

```
ffffffff8123dc00-ffffffff8123ddb0: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125d790)
Location: mm/memcontrol.c:4870
Inline: True
```
**Symbols:**

```
ffffffff8125d790-ffffffff8125d940: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81281e20)
Location: mm/memcontrol.c:4807
Inline: True
```
**Symbols:**

```
ffffffff81281e20-ffffffff81281fcd: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81299510)
Location: mm/memcontrol.c:5093
Inline: True
```
**Symbols:**

```
ffffffff81299510-ffffffff812996bd: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b4860)
Location: mm/memcontrol.c:5454
Inline: True
```
**Symbols:**

```
ffffffff812b4860-ffffffff812b4a0d: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6180)
Location: mm/memcontrol.c:5794
Inline: True
```
**Symbols:**

```
ffffffff812c6180-ffffffff812c6300: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812fb6e0)
Location: mm/memcontrol.c:5700
Inline: True
```
**Symbols:**

```
ffffffff812fb6e0-ffffffff812fb8a8: mem_cgroup_can_attach.part.0 (STB_LOCAL)
ffffffff812fb8b0-ffffffff812fb8c8: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81307b30)
Location: mm/memcontrol.c:5934
Inline: True
```
**Symbols:**

```
ffffffff81307b30-ffffffff81307cc5: mem_cgroup_can_attach.part.0 (STB_LOCAL)
ffffffff81307cd0-ffffffff81307ce8: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130e2e0)
Location: mm/memcontrol.c:5756
Inline: True
```
**Symbols:**

```
ffffffff8130e2e0-ffffffff8130e498: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81359110)
Location: mm/memcontrol.c:5940
Inline: True
```
**Symbols:**

```
ffffffff81359110-ffffffff813592b9: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d29c0)
Location: mm/memcontrol.c:5886
Inline: False
```
**Symbols:**

```
ffffffff813d29c0-ffffffff813d2bf1: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814581a0)
Location: mm/memcontrol.c:6051
Inline: False
```
**Symbols:**

```
ffffffff814581a0-ffffffff814583cd: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148dee0)
Location: mm/memcontrol.c:6113
Inline: False
```
**Symbols:**

```
ffffffff8148dee0-ffffffff8148e110: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bd860)
Location: mm/memcontrol.c:6348
Inline: False
```
**Symbols:**

```
ffffffff814bd860-ffffffff814bda90: mem_cgroup_can_attach (STB_LOCAL)
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
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010368e48)
Location: mm/memcontrol.c:5794
Inline: True
```
**Symbols:**

```
ffff800010368e48-ffff800010368ff8: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055a3d4)
Location: mm/memcontrol.c:5794
Inline: True
```
**Symbols:**

```
c055a3d4-c055a5b4: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0000000004572c0)
Location: mm/memcontrol.c:5794
Inline: True
```
**Symbols:**

```
c0000000004572c0-c000000000457544: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000246a76)
Location: mm/memcontrol.c:5794
Inline: True
```
**Symbols:**

```
ffffffe000246a76-ffffffe000246bf6: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be760)
Location: mm/memcontrol.c:5794
Inline: True
```
**Symbols:**

```
ffffffff812be760-ffffffff812be8e0: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812af850)
Location: mm/memcontrol.c:5794
Inline: True
```
**Symbols:**

```
ffffffff812af850-ffffffff812af9d0: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bc570)
Location: mm/memcontrol.c:5794
Inline: True
```
**Symbols:**

```
ffffffff812bc570-ffffffff812bc6f0: mem_cgroup_can_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mem_cgroup_can_attach(struct cgroup_taskset *tset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ccd50)
Location: mm/memcontrol.c:5794
Inline: True
```
**Symbols:**

```
ffffffff812ccd50-ffffffff812ccece: mem_cgroup_can_attach (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
