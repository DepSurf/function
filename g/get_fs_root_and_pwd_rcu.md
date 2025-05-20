# Function: <code>get_fs_root_and_pwd_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812263e9)
Location: fs/dcache.c:3208
Inline: True
Inline callers:
  - fs/dcache.c:SyS_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124ea89)
Location: fs/dcache.c:3375
Inline: True
Inline callers:
  - fs/dcache.c:SyS_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81261a99)
Location: fs/dcache.c:3385
Inline: True
Inline callers:
  - fs/dcache.c:SyS_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126f37a)
Location: fs/dcache.c:3415
Inline: True
Inline callers:
  - fs/dcache.c:SyS_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81291c9a)
Location: fs/dcache.c:3427
Inline: True
Inline callers:
  - fs/dcache.c:SyS_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff812d3d0b)
Location: fs/d_path.c:394
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff812e8f5b)
Location: fs/d_path.c:394
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813077eb)
Location: fs/d_path.c:393
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8131a85b)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
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
In fs/d_path.c (ffffffff81354784)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
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
In fs/d_path.c (ffffffff81361094)
Location: fs/d_path.c:399
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
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
In fs/d_path.c (ffffffff81367b74)
Location: fs/d_path.c:399
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
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
In fs/d_path.c (ffffffff813b6724)
Location: fs/d_path.c:384
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
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
In fs/d_path.c (ffffffff8143bd1a)
Location: fs/d_path.c:382
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
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
In fs/d_path.c (ffffffff814ca34a)
Location: fs/d_path.c:381
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
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
In fs/d_path.c (ffffffff8150058a)
Location: fs/d_path.c:382
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
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
In fs/d_path.c (ffffffff815351aa)
Location: fs/d_path.c:382
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffff8000103d1ddc)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__arm64_sys_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c05acecc)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c0000000004d468c)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffe00028d704)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81312e3b)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81303a4b)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81310c2b)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81322460)
Location: fs/d_path.c:395
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
```
</details>
</li>
</ul>

## Differences
