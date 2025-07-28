# Repository Details User Stories

## Epic: Repository Issue Overview
As a maintainer, I want to see detailed information about a specific repository and its issues so I can understand the project's health and prioritize work.

### US-RD-001: View Repository Overview
**As a** repository maintainer  
**I want to** see comprehensive repository information  
**So that** I can understand the project's current state and metrics  

**Acceptance Criteria:**
- Display repository full name (owner/repo)
- Show repository description or "No description available"
- Display key metrics: language, stars count, forks count, last updated date
- Show private badge for private repositories
- Include breadcrumb navigation: Home > Repository Name
- Repository header loads with skeleton while fetching data

**Priority:** High  
**Story Points:** 3

### US-RD-002: View Repository Issues List
**As a** repository maintainer  
**I want to** see all issues for a repository in a table format  
**So that** I can quickly scan and prioritize issues  

**Acceptance Criteria:**
- Display issues in a responsive table with columns: Issue, State, Labels, Comments, AI Analysis, Updated
- Show issue number, title, and author for each issue
- Display issue state with appropriate badge (open/closed)
- Show up to 3 labels with colors, plus count if more exist
- Display comments count
- Show AI analysis intent and priority score when available
- Include last updated date
- Table rows are clickable and navigate to issue details
- Show empty state when no issues exist

**Priority:** High  
**Story Points:** 5

### US-RD-003: Repository Issues Pagination
**As a** repository maintainer  
**I want to** navigate through multiple pages of issues  
**So that** I can browse large numbers of issues efficiently  

**Acceptance Criteria:**
- Implement pagination controls for issues table
- Show current page and total pages
- Navigation buttons for previous/next page
- Load issues with skeleton loading states
- Maintain pagination state when navigating back to page

**Priority:** Medium  
**Story Points:** 3

### US-RD-004: Refresh Repository Issues
**As a** repository maintainer  
**I want to** manually refresh issue data  
**So that** I can see the latest issue information  

**Acceptance Criteria:**
- "Refresh" button in issues section header
- Button shows loading state during refresh
- Updates issue list with latest data from API
- Show skeleton loading during refresh
- Display error notifications if refresh fails

**Priority:** Medium  
**Story Points:** 2

### US-RD-005: Repository Metrics Dashboard
**As a** repository maintainer  
**I want to** see key repository metrics at a glance  
**So that** I can quickly assess repository health  

**Acceptance Criteria:**
- Display open issues count prominently
- Show labels breakdown with counts
- Include recent activity indicators
- Show AI analysis summary statistics (if available)
- Metrics update when repository data refreshes

**Priority:** Medium  
**Story Points:** 4

### US-RD-006: Filter and Sort Issues
**As a** repository maintainer  
**I want to** filter and sort issues by various criteria  
**So that** I can find specific issues quickly  

**Acceptance Criteria:**
- Filter by issue state (open/closed)
- Filter by labels
- Filter by AI analysis intent (bug, feature request, etc.)
- Sort by updated date, comments count, priority score
- Filters persist during pagination
- Clear filters option available

**Priority:** Low  
**Story Points:** 6