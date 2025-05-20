# Function: <code>nvdimm_bus_destroy_ndctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81597ca0)
Location: drivers/nvdimm/bus.c:329
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_unregister
```
**Symbols:**

```
ffffffff81597ca0-ffffffff81597cc6: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ecd1b)
Location: drivers/nvdimm/bus.c:590
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff815ed5b0-ffffffff815ed5d6: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81619b0b)
Location: drivers/nvdimm/bus.c:592
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff8161a3c0-ffffffff8161a3e6: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162db09)
Location: drivers/nvdimm/bus.c:655
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff8162e4c0-ffffffff8162e4e6: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816962c9)
Location: drivers/nvdimm/bus.c:655
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81696c80-ffffffff81696ca6: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d23b0)
Location: drivers/nvdimm/bus.c:663
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff816d2de0-ffffffff816d2e06: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f3820)
Location: drivers/nvdimm/bus.c:692
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff816f4510-ffffffff816f4536: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172d19b)
Location: drivers/nvdimm/bus.c:723
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff8172db00-ffffffff8172db26: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817511db)
Location: drivers/nvdimm/bus.c:721
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81751da0-ffffffff81751dc6: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8180faa8)
Location: drivers/nvdimm/bus.c:753
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff818106f0-ffffffff81810716: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181e9e8)
Location: drivers/nvdimm/bus.c:750
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff8181f630-ffffffff8181f656: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81801d58)
Location: drivers/nvdimm/bus.c:745
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81802940-ffffffff81802966: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188c258)
Location: drivers/nvdimm/bus.c:762
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff8188ce80-ffffffff8188cea6: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d55e6)
Location: drivers/nvdimm/bus.c:753
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff819d63a0-ffffffff819d63ce: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b50086)
Location: drivers/nvdimm/bus.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81b51020-ffffffff81b5104e: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba3556)
Location: drivers/nvdimm/bus.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81ba44c0-ffffffff81ba44ee: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf7746)
Location: drivers/nvdimm/bus.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81bf86e0-ffffffff81bf870e: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
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
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010951b80)
Location: drivers/nvdimm/bus.c:721
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffff800010952520-ffff800010952560: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fdacc)
Location: drivers/nvdimm/bus.c:721
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
c0000000009ff400-c0000000009ff458: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c147e)
Location: drivers/nvdimm/bus.c:721
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffe0005c203e-ffffffe0005c2082: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
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
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817058cb)
Location: drivers/nvdimm/bus.c:721
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81706490-ffffffff817064b6: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d934b)
Location: drivers/nvdimm/bus.c:721
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff816d9f10-ffffffff816d9f36: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8174469b)
Location: drivers/nvdimm/bus.c:721
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81745260-ffffffff81745286: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_destroy_ndctl(struct nvdimm_bus *nvdimm_bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8175fadf)
Location: drivers/nvdimm/bus.c:721
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff817606a0-ffffffff817606c6: nvdimm_bus_destroy_ndctl (STB_GLOBAL)
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
