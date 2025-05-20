# Function: <code>devlink_trap_unregister</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81983f10)
Location: net/core/devlink.c:7839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81983f10-ffffffff81983fc5: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ed30)
Location: net/core/devlink.c:8777
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81a5ed30-ffffffff81a5ee18: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a65b90)
Location: net/core/devlink.c:9735
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81a65b90-ffffffff81a65c78: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4b350)
Location: net/core/devlink.c:9999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81a4b350-ffffffff81a4b438: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b03bc0)
Location: net/core/devlink.c:10941
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81b03bc0-ffffffff81b03ca8: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c85120)
Location: net/core/devlink.c:11537
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81c85120-ffffffff81c85219: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3f2b0)
Location: net/core/devlink.c:12353
Inline: False
Direct callers:
  - net/core/devlink.c:devl_traps_unregister
```
**Symbols:**

```
ffffffff81e3f2b0-ffffffff81e3f3a9: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203fa70)
Location: net/devlink/leftover.c:8948
Inline: False
Direct callers:
  - net/devlink/leftover.c:devl_traps_unregister
```
**Symbols:**

```
ffffffff8203fa70-ffffffff8203fb69: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82116510)
Location: net/devlink/trap.c:1315
Inline: False
Direct callers:
  - net/devlink/trap.c:devl_traps_unregister
```
**Symbols:**

```
ffffffff82116510-ffffffff82116609: devlink_trap_unregister (STB_LOCAL)
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
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2c548)
Location: net/core/devlink.c:7839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffff800010c2c548-ffff800010c2c620: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d430ec)
Location: net/core/devlink.c:7839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
c0d430ec-c0d431cc: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d23260)
Location: net/core/devlink.c:7839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
c000000000d23260-c000000000d23380: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a3a66)
Location: net/core/devlink.c:7839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffe0007a3a66-ffffffe0007a3b1a: devlink_trap_unregister (STB_LOCAL)
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
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81923d80)
Location: net/core/devlink.c:7839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81923d80-ffffffff81923e35: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818ddb30)
Location: net/core/devlink.c:7839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff818ddb30-ffffffff818ddbe5: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81974f10)
Location: net/core/devlink.c:7839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81974f10-ffffffff81974fc5: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_trap_unregister(struct devlink *devlink, const struct devlink_trap *trap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81997400)
Location: net/core/devlink.c:7839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81997400-ffffffff819974b5: devlink_trap_unregister (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
