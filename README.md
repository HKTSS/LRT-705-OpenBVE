# MTR Light Rail 705 for OpenBVE
This is an attempt at re-creating the MTR Light Rail 705 route for the train simulator [OpenBVE](https://github.com/leezer3/OpenBVE).  
Last tested OpenBVE version is v1.9.0.0.  

**This project is Work In Progress, and development is stagnet, see below.**

## Development
The current developed section only includes **Tin Tsz, Tin Wu and Ginza station**, and primary development has fully stalled in ~November 2022.

The original goal is to make a phase 1 release for the section from **Tin Tsz -> Wetland Park**.  
However due to the shear amount of work and an (arguably) outdated development method, this project will likely remain dormant. And even with active development, it will be a multi-year journey to get the whole or even half the route done.

Nevertheless it is released to the public for potential new people to look into the development of OpenBVE, the behind the scenes, and also I just think it's a bit of a waste having spent too much time on something that will never see the light of day.

Contributing is always welcomed, whether big or small. And perhaps one day enough progress can be made to fulfill the original goal.

## Stage (New 2025 Plan)
### 1: Rework Rail Alignment
The existing rail alignment is not geographically accurate, which makes it quite hard to model the scenery (And causes more problem down the line)

The rail alignment including all scenery needed to be modified to match the digital map by Lands Department.

- [x] Rework main rail alignment
- [ ] Adapt scenery to new alignment
- [ ] Re-organize route file (Rework indexes)

### 2: LRT Station Structure
Work on station structure for each LRT stop

### 3: Landmark building
Work on buildings/structure which are prominently visible in the main LRT 705 line. (Residential building, TIS station etc.)

### 4: Additional Rail
Work on other non-main line rail. This stage should also start evaluate the need to move to 5m block instead of 25m (There is performance concern for 5m)

### 5: Road
Work on ground-level detail such as road, bridges & nearby infrastructure

### 6: Finalization
Finalize any detail that's still missing at this point

## License
This work is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0)