# Function: <code>__nd_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81597da0)
Location: drivers/nvdimm/bus.c:482
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff81597da0-ffffffff815982e9: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ed6b0)
Location: drivers/nvdimm/bus.c:791
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff815ed6b0-ffffffff815eddad: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8161a4b0)
Location: drivers/nvdimm/bus.c:808
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff8161a4b0-ffffffff8161abb5: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162e5b0)
Location: drivers/nvdimm/bus.c:910
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff8162e5b0-ffffffff8162edcf: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81696d70)
Location: drivers/nvdimm/bus.c:910
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff81696d70-ffffffff81697538: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d2ed0)
Location: drivers/nvdimm/bus.c:918
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff816d2ed0-ffffffff816d3682: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f4600)
Location: drivers/nvdimm/bus.c:947
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff816f4600-ffffffff816f4d83: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:980
Inline: False
```
**Symbols:**

```
ffffffff8172dc10-ffffffff8172e51e: __nd_ioctl (STB_LOCAL)
ffffffff8172e7e5-ffffffff8172e829: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:978
Inline: False
```
**Symbols:**

```
ffffffff81751eb0-ffffffff817527be: __nd_ioctl (STB_LOCAL)
ffffffff81752a34-ffffffff81752a78: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:1010
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff81810800-ffffffff818111f2: __nd_ioctl (STB_LOCAL)
ffffffff81811464-ffffffff818114a8: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:1007
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff8181f740-ffffffff81820133: __nd_ioctl (STB_LOCAL)
ffffffff81c15acf-ffffffff81c15b13: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:1002
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff81802a50-ffffffff8180341f: __nd_ioctl (STB_LOCAL)
ffffffff81c07827-ffffffff81c0786b: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:1019
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff8188cf90-ffffffff8188d99b: __nd_ioctl (STB_LOCAL)
ffffffff81d0ae5a-ffffffff81d0ae9e: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:1010
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff819d64f0-ffffffff819d6eba: __nd_ioctl (STB_LOCAL)
ffffffff81ed32fc-ffffffff81ed3345: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b51190)
Location: drivers/nvdimm/bus.c:1023
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff81b51190-ffffffff81b51b8a: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba4630)
Location: drivers/nvdimm/bus.c:1023
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff81ba4630-ffffffff81ba5067: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf8850)
Location: drivers/nvdimm/bus.c:1023
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffff81bf8850-ffffffff81bf92e4: __nd_ioctl (STB_LOCAL)
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
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010952668)
Location: drivers/nvdimm/bus.c:978
Inline: False
```
**Symbols:**

```
ffff800010952668-ffff800010952d64: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009ff5e0)
Location: drivers/nvdimm/bus.c:978
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
c0000000009ff5e0-c0000000009ffe90: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c215c)
Location: drivers/nvdimm/bus.c:978
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
**Symbols:**

```
ffffffe0005c215c-ffffffe0005c2898: __nd_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:978
Inline: False
```
**Symbols:**

```
ffffffff817065a0-ffffffff81706eae: __nd_ioctl (STB_LOCAL)
ffffffff81707124-ffffffff81707168: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:978
Inline: False
```
**Symbols:**

```
ffffffff816da020-ffffffff816da92e: __nd_ioctl (STB_LOCAL)
ffffffff816daba4-ffffffff816dabe8: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:978
Inline: False
```
**Symbols:**

```
ffffffff81745370-ffffffff81745c7e: __nd_ioctl (STB_LOCAL)
ffffffff81745ef4-ffffffff81745f38: __nd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __nd_ioctl(struct nvdimm_bus *nvdimm_bus, struct nvdimm *nvdimm, int read_only, unsigned int ioctl_cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:978
Inline: False
```
**Symbols:**

```
ffffffff817607b0-ffffffff817610be: __nd_ioctl (STB_LOCAL)
ffffffff81761334-ffffffff81761378: __nd_ioctl.cold (STB_LOCAL)
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
