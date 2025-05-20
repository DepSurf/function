# Function: <code>nvdimm_request_key</code>

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
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81703d30)
Location: drivers/nvdimm/security.c:48
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81703d30-ffffffff81703e2b: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8173d9a0)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8173d9a0-ffffffff8173daa3: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81761820)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81761820-ffffffff81761923: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff818214b0)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
```
**Symbols:**

```
ffffffff818214b0-ffffffff818215b3: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff818301c0)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
```
**Symbols:**

```
ffffffff818301c0-ffffffff818302c3: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81813450)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81813450-ffffffff81813553: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8189da90)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8189da90-ffffffff8189db8d: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff819e74d0)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff819e74d0-ffffffff819e75f1: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81b63700)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81b63700-ffffffff81b63823: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81bb6d00)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81bb6d00-ffffffff81bb6e23: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81c0b350)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81c0b350-ffffffff81c0b473: nvdimm_request_key (STB_LOCAL)
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
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffff800010961740)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffff800010961740-ffff800010961874: nvdimm_request_key (STB_LOCAL)
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
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (c000000000a172a0)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
c000000000a172a0-c000000000a17418: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffe0005cefd6)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffe0005cefd6-ffffffe0005cf0e6: nvdimm_request_key (STB_LOCAL)
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
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81715f10)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81715f10-ffffffff81716013: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff816e9990)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff816e9990-ffffffff816e9a93: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81754ce0)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81754ce0-ffffffff81754de3: nvdimm_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *nvdimm_request_key(struct nvdimm *nvdimm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81770150)
Location: drivers/nvdimm/security.c:50
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81770150-ffffffff81770253: nvdimm_request_key (STB_LOCAL)
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
