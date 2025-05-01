<!DOCTYPE html>
<html>
<body>
    <h1>Netflix Content Analysis Case Study</h1>
    <h2>Overview</h2>
    <p>This case study analyzes a Netflix dataset (<code>netflix.csv</code>) to uncover content distribution trends, geographic preferences, temporal patterns, and actionable business recommendations. The dataset includes 8,807 entries across 12 columns (e.g., title, director, country, genre, release year).</p>

  <h2>Key Insights</h2>
  
  <h3>1. Content Distribution</h3>
  <ul>
      <li><strong>Movies dominate</strong>: 69% of Netflix content is movies; TV shows account for 31%.</li>
      <li><strong>Duration trends</strong>:
          <ul>
              <li>Movies: Most are 80–120 minutes (peaking at 90–100 minutes).</li>
              <li>TV shows: Single-season releases are preferred.</li>
          </ul>
      </li>
      <li><strong>Genres</strong>:
          <ul>
              <li>Movies: Top genres are Dramas, Comedies, and Documentaries.</li>
              <li>TV Shows: Crime, Dramas, and International content thrive.</li>
          </ul>
      </li>
  </ul>

  <h3>2. Geographic Trends</h3>
  <ul>
      <li><strong>Top content producers</strong>: United States (37%), India (10%), United Kingdom (9%).</li>
      <li><strong>Regional preferences</strong>:
          <ul>
              <li>Japan and South Korea lead in TV shows (Anime/K-Dramas).</li>
              <li>India focuses on International Movies and Dramas.</li>
          </ul>
      </li>
  </ul>

  <h3>3. Temporal Analysis</h3>
  <ul>
      <li><strong>Release trends</strong>: Content production surged post-2015 but declined post-2019 (COVID-19 impact).</li>
      <li><strong>Seasonal patterns</strong>: Consistent content additions year-round, with peaks in December.</li>
      <li><strong>Delayed releases</strong>: Most content is added to Netflix years after its original release.</li>
  </ul>

  <h3>4. Ratings & Talent</h3>
  <ul>
      <li><strong>Ratings</strong>: TV-MA (mature audiences) is the most common.</li>
      <li><strong>Top creators</strong>: Rajiv Chilaka (movies), Ken Burns (TV shows).</li>
      <li><strong>Actors</strong>: Indian actors dominate movie credits (e.g., Anupam Kher).</li>
  </ul>

  <h2>Recommendations</h2>
  <ol>
      <li><strong>Content Strategy</strong>:
          <ul>
              <li>Invest in high-quality, binge-worthy TV shows (e.g., anthologies).</li>
              <li>Prioritize family-friendly (General/G) content for broader reach.</li>
          </ul>
      </li>
      <li><strong>Regional Growth</strong>:
          <ul>
              <li>Expand localized content (e.g., Chinese collaborations, regional storytelling).</li>
              <li>Capitalize on global holidays (e.g., Christmas/Diwali releases).</li>
          </ul>
      </li>
      <li><strong>Operational Improvements</strong>:
          <ul>
              <li>Reduce delays in content acquisition; focus on Netflix Originals.</li>
              <li>Optimize movie durations by genre (e.g., shorter comedies, longer dramas).</li>
          </ul>
      </li>
  </ol>

  <h2>Methodology</h2>
  <ul>
      <li><strong>Data Cleaning</strong>:
          <ul>
              <li>Filled missing values (e.g., "Unknown" for directors/cast).</li>
              <li>Converted <code>date_added</code> to datetime and split multi-value columns (genres, cast).</li>
          </ul>
      </li>
      <li><strong>Analysis</strong>:
          <ul>
              <li>Visualized trends with histograms, heatmaps, and line plots.</li>
              <li>Compared metrics across countries, genres, and time periods.</li>
          </ul>
      </li>
  </ul>

  <h2>Tools Used</h2>
  <ul>
      <li>Python (<code>Pandas</code>, <code>NumPy</code>)</li>
      <li><code>Matplotlib</code>, <code>Seaborn</code></li>
  </ul>
</body>
</html>
