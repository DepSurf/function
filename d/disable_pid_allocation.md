# Function: <code>disable_pid_allocation</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109e5a0)
Location: kernel/pid.c:359
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff8109e5a0-ffffffff8109e5db: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1c40)
Location: kernel/pid.c:359
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a1c40-ffffffff810a1c7b: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6d00)
Location: kernel/pid.c:359
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a6d00-ffffffff810a6d3b: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3bf8)
Location: kernel/pid.c:360
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a3c40-ffffffff810a3c7b: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aa230)
Location: kernel/pid.c:237
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810aa230-ffffffff810aa268: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0e40)
Location: kernel/pid.c:249
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810b0e40-ffffffff810b0e78: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9f40)
Location: kernel/pid.c:251
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810b9f40-ffffffff810b9f78: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfe50)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810bfe50-ffffffff810bfe88: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c6220)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810c6220-ffffffff810c6258: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ce0a0)
Location: kernel/pid.c:301
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810ce0a0-ffffffff810ce0db: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8b70)
Location: kernel/pid.c:302
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810c8b70-ffffffff810c8bab: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca610)
Location: kernel/pid.c:302
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810ca610-ffffffff810ca64b: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd460)
Location: kernel/pid.c:302
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810dd460-ffffffff810dd49b: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f6d50)
Location: kernel/pid.c:302
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810f6d50-ffffffff810f6d88: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119440)
Location: kernel/pid.c:302
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff81119440-ffffffff81119478: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126910)
Location: kernel/pid.c:305
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff81126910-ffffffff81126948: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81130f00)
Location: kernel/pid.c:305
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff81130f00-ffffffff81130f38: disable_pid_allocation (STB_GLOBAL)
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
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff8000101249d8)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffff8000101249d8-ffff800010124a78: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377a3c)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
c0377a3c-c0377a90: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016e770)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
c00000000016e770-c00000000016e810: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc9a6)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffe0000dc9a6-ffffffe0000dca26: disable_pid_allocation (STB_GLOBAL)
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
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c05a0)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810c05a0-ffffffff810c05d8: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aeda0)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810aeda0-ffffffff810aedd2: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfaf0)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810bfaf0-ffffffff810bfb28: disable_pid_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void disable_pid_allocation(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7f10)
Location: kernel/pid.c:254
Inline: False
Direct callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810c7f10-ffffffff810c7f3f: disable_pid_allocation (STB_GLOBAL)
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
