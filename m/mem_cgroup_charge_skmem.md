# Function: <code>mem_cgroup_charge_skmem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812242b0)
Location: mm/memcontrol.c:5722
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff812242b0-ffffffff81224399: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236880)
Location: mm/memcontrol.c:5710
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff81236880-ffffffff81236969: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81242320)
Location: mm/memcontrol.c:5772
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff81242320-ffffffff8124240c: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81262120)
Location: mm/memcontrol.c:5871
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff81262120-ffffffff8126220c: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286120)
Location: mm/memcontrol.c:5939
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff81286120-ffffffff8128625d: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129b070)
Location: mm/memcontrol.c:6270
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff8129b070-ffffffff8129b1b0: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6340)
Location: mm/memcontrol.c:6562
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff812b6340-ffffffff812b6448: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c8210)
Location: mm/memcontrol.c:6892
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff812c8210-ffffffff812c8318: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fda70)
Location: mm/memcontrol.c:6750
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff812fda70-ffffffff812fdb7d: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309ec0)
Location: mm/memcontrol.c:7010
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff81309ec0-ffffffff81309fcd: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310730)
Location: mm/memcontrol.c:6871
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff81310730-ffffffff8131083d: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135ba40)
Location: mm/memcontrol.c:7053
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff8135ba40-ffffffff8135bb3a: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d5320)
Location: mm/memcontrol.c:7033
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff813d5320-ffffffff813d5408: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145adc0)
Location: mm/memcontrol.c:7222
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff8145adc0-ffffffff8145aea5: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81490a30)
Location: mm/memcontrol.c:7290
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff81490a30-ffffffff81490b15: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c03a0)
Location: mm/memcontrol.c:7667
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff814c03a0-ffffffff814c0485: mem_cgroup_charge_skmem (STB_GLOBAL)
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
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036b108)
Location: mm/memcontrol.c:6892
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffff80001036b108-ffff80001036b220: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c838)
Location: mm/memcontrol.c:6892
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
c055c838-c055c948: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045a960)
Location: mm/memcontrol.c:6892
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
c00000000045a960-c00000000045aac8: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002488a0)
Location: mm/memcontrol.c:6892
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffe0002488a0-ffffffe000248978: mem_cgroup_charge_skmem (STB_GLOBAL)
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
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c07f0)
Location: mm/memcontrol.c:6892
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff812c07f0-ffffffff812c08f8: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b18b0)
Location: mm/memcontrol.c:6892
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff812b18b0-ffffffff812b19a4: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be600)
Location: mm/memcontrol.c:6892
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff812be600-ffffffff812be708: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cf060)
Location: mm/memcontrol.c:6892
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
**Symbols:**

```
ffffffff812cf060-ffffffff812cf168: mem_cgroup_charge_skmem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
