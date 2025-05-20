# Function: <code>nvdimm_security_freeze</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5ff0)
Location: drivers/nvdimm/dimm_devs.c:609
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff816f5ff0-ffffffff816f609a: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:__security_store
```
**Symbols:**

```
ffffffff817301f0-ffffffff8173020a: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff8172f7b0-ffffffff8172f84f: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:536
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81754289-ffffffff817542a3: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81753c70-ffffffff81753d7f: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:543
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81812e89-ffffffff81812ea3: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81812720-ffffffff8181282f: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:673
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81c15b13-ffffffff81c15b2d: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81821970-ffffffff81821a7f: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:673
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81c0786b-ffffffff81c07885: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81804c90-ffffffff81804d9f: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:691
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81d0af20-ffffffff81d0af4f: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff8188f3f0-ffffffff8188f50e: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:672
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81ed33b6-ffffffff81ed33e5: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff819d8990-ffffffff819d8ac2: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:682
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff8209a69f-ffffffff8209a6b4: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81b53900-ffffffff81b53a41: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:682
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff8211b777-ffffffff8211b78c: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81ba6e00-ffffffff81ba6f3f: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:684
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff821f95fe-ffffffff821f9613: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81bfb0b0-ffffffff81bfb1ef: nvdimm_security_freeze (STB_GLOBAL)
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
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff8000109546a0)
Location: drivers/nvdimm/dimm_devs.c:536
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffff8000109546a0-ffff8000109547c8: nvdimm_security_freeze (STB_GLOBAL)
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
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a01c80)
Location: drivers/nvdimm/dimm_devs.c:536
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
c000000000a01c80-c000000000a01e2c: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3e48)
Location: drivers/nvdimm/dimm_devs.c:536
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffe0005c3e48-ffffffe0005c3f2a: nvdimm_security_freeze (STB_GLOBAL)
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
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:536
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81708979-ffffffff81708993: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81708360-ffffffff8170846f: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:536
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff816dc3f9-ffffffff816dc413: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff816dbde0-ffffffff816dbeef: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:536
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81747749-ffffffff81747763: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81747130-ffffffff8174723f: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nvdimm_security_freeze(struct nvdimm *nvdimm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:536
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81762b89-ffffffff81762ba3: nvdimm_security_freeze.cold (STB_LOCAL)
ffffffff81762570-ffffffff8176267f: nvdimm_security_freeze (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
