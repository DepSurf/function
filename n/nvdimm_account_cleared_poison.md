# Function: <code>nvdimm_account_cleared_poison</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162d780)
Location: drivers/nvdimm/bus.c:220
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff8162d780-ffffffff8162d7fb: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81695f30)
Location: drivers/nvdimm/bus.c:221
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff81695f30-ffffffff81695fb2: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d2000)
Location: drivers/nvdimm/bus.c:224
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff816d2000-ffffffff816d2082: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f3860)
Location: drivers/nvdimm/bus.c:218
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff816f3860-ffffffff816f38e2: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172cbc0)
Location: drivers/nvdimm/bus.c:217
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff8172cbc0-ffffffff8172cc42: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81750de0)
Location: drivers/nvdimm/bus.c:215
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff81750de0-ffffffff81750e62: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181110c)
Location: drivers/nvdimm/bus.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8182004d)
Location: drivers/nvdimm/bus.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81803339)
Location: drivers/nvdimm/bus.c:214
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188d893)
Location: drivers/nvdimm/bus.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d6b63)
Location: drivers/nvdimm/bus.c:204
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b51a9d)
Location: drivers/nvdimm/bus.c:204
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba4f47)
Location: drivers/nvdimm/bus.c:204
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf91c4)
Location: drivers/nvdimm/bus.c:204
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
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
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010951078)
Location: drivers/nvdimm/bus.c:215
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffff800010951078-ffff80001095110c: nvdimm_account_cleared_poison (STB_LOCAL)
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
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fdd20)
Location: drivers/nvdimm/bus.c:215
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
c0000000009fdd20-c0000000009fde00: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c0ff4)
Location: drivers/nvdimm/bus.c:215
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffe0005c0ff4-ffffffe0005c106a: nvdimm_account_cleared_poison (STB_LOCAL)
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
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817054d0)
Location: drivers/nvdimm/bus.c:215
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff817054d0-ffffffff81705552: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d8f50)
Location: drivers/nvdimm/bus.c:215
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff816d8f50-ffffffff816d8fd2: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817442a0)
Location: drivers/nvdimm/bus.c:215
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff817442a0-ffffffff81744322: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_account_cleared_poison(struct nvdimm_bus *nvdimm_bus, phys_addr_t phys, u64 cleared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8175f6f0)
Location: drivers/nvdimm/bus.c:215
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff8175f6f0-ffffffff8175f772: nvdimm_account_cleared_poison (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
