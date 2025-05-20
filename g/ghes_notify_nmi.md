# Function: <code>ghes_notify_nmi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff814b65f0)
Location: drivers/acpi/apei/ghes.c:838
Inline: False
```
**Symbols:**

```
ffffffff814b65f0-ffffffff814b67ef: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81505fc0)
Location: drivers/acpi/apei/ghes.c:843
Inline: False
```
**Symbols:**

```
ffffffff81505fc0-ffffffff815061c8: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8152a1c0)
Location: drivers/acpi/apei/ghes.c:843
Inline: False
```
**Symbols:**

```
ffffffff8152a1c0-ffffffff8152a3dd: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8153c990)
Location: drivers/acpi/apei/ghes.c:970
Inline: True
```
**Symbols:**

```
ffffffff8153c990-ffffffff8153cb54: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8159f4a0)
Location: drivers/acpi/apei/ghes.c:919
Inline: True
```
**Symbols:**

```
ffffffff8159f4a0-ffffffff8159f664: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815d7180)
Location: drivers/acpi/apei/ghes.c:932
Inline: False
```
**Symbols:**

```
ffffffff815d7180-ffffffff815d7326: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815f07b0)
Location: drivers/acpi/apei/ghes.c:1004
Inline: True
```
**Symbols:**

```
ffffffff815f07b0-ffffffff815f0aae: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816227a0)
Location: drivers/acpi/apei/ghes.c:996
Inline: True
```
**Symbols:**

```
ffffffff816227a0-ffffffff81622857: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81644280)
Location: drivers/acpi/apei/ghes.c:1009
Inline: True
```
**Symbols:**

```
ffffffff81644280-ffffffff81644337: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816f2310)
Location: drivers/acpi/apei/ghes.c:1048
Inline: True
```
**Symbols:**

```
ffffffff816f2310-ffffffff816f23a2: ghes_notify_nmi.part.0 (STB_LOCAL)
ffffffff816f23b0-ffffffff816f23db: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8170f6d0)
Location: drivers/acpi/apei/ghes.c:1111
Inline: True
```
**Symbols:**

```
ffffffff8170f6d0-ffffffff8170f76c: ghes_notify_nmi.part.0 (STB_LOCAL)
ffffffff8170f770-ffffffff8170f79b: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816f0fb0)
Location: drivers/acpi/apei/ghes.c:1158
Inline: True
```
**Symbols:**

```
ffffffff816f0fb0-ffffffff816f106d: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8176b0c0)
Location: drivers/acpi/apei/ghes.c:1158
Inline: True
```
**Symbols:**

```
ffffffff8176b0c0-ffffffff8176b17d: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8189fca0)
Location: drivers/acpi/apei/ghes.c:1158
Inline: True
```
**Symbols:**

```
ffffffff8189fca0-ffffffff8189fd72: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e90a0)
Location: drivers/acpi/apei/ghes.c:1180
Inline: True
```
**Symbols:**

```
ffffffff819e90a0-ffffffff819e9172: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a317b0)
Location: drivers/acpi/apei/ghes.c:1178
Inline: True
```
**Symbols:**

```
ffffffff81a317b0-ffffffff81a31882: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7cc20)
Location: drivers/acpi/apei/ghes.c:1216
Inline: True
```
**Symbols:**

```
ffffffff81a7cc20-ffffffff81a7ccf2: ghes_notify_nmi (STB_LOCAL)
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
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816380c0)
Location: drivers/acpi/apei/ghes.c:1009
Inline: True
```
**Symbols:**

```
ffffffff816380c0-ffffffff81638177: ghes_notify_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ghes_notify_nmi(unsigned int cmd, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816523f0)
Location: drivers/acpi/apei/ghes.c:1009
Inline: True
```
**Symbols:**

```
ffffffff816523f0-ffffffff816524ba: ghes_notify_nmi (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
