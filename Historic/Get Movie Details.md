
You have already made a movie details page.

#### Acceptance Criteria
- URL: `/movies-details/:{movie-id}` We should see the movie details.
	- Update React Router URL.
- API: `https://api.themoviedb.org/3/movie/{movie_id}`
	-  method: GET
	- function name: `getMovieDetails(movieId)=> returns movie-details`
	- url: `movie/{movie_id}` -> movie-id is dynamic

#### What should be shown in the screen?
1. title
2. poster
3. Release date
4. Budget 
5. Genres ()
6. Original Language
7. Overview
8. Revenue: (*How much the movie earns*)
9. Spoken Language
10. Tagline
11. runtime
12. production_countries


- Example Response:
```json
{
  "adult": false,
  "backdrop_path": "/s3TBrRGB1iav7gFOCNx3H31MoES.jpg",
  "belongs_to_collection": {
    "id": 2344,
    "name": "Inception Collection",
    "poster_path": "/xx9j0nzI2EoG6oH2zP4VLMKkvtg.jpg",
    "backdrop_path": "/jHZkw3GA1IMNdadUBGVpWaF29sh.jpg"
  },
  "budget": 160000000,
  "genres": [
    { "id": 28, "name": "Action" },
    { "id": 878, "name": "Science Fiction" },
    { "id": 12, "name": "Adventure" }
  ],
  "homepage": "http://inceptionmovie.warnerbros.com/",
  "id": 27205,
  "imdb_id": "tt1375666",
  "original_language": "en",
  "original_title": "Inception",
  "overview": "Cobb, a skilled thief who commits corporate espionage by infiltrating the subconscious of his targets...",
  "popularity": 78.918,
  "poster_path": "/9gk7adHYeDvHkCSEqAvQNLV5Uge.jpg",
  "production_companies": [
    {
      "id": 923,
      "logo_path": "/5UQsZrfbfG2dYJbx8DxfoTr2W8A.png",
      "name": "Legendary Entertainment",
      "origin_country": "US"
    },
    {
      "id": 9996,
      "logo_path": "/3tvBqYsBhxWeHlu62SIJ1el93O7.png",
      "name": "Syncopy",
      "origin_country": "GB"
    }
  ],
  "production_countries": [
    { "iso_3166_1": "US", "name": "United States of America" },
    { "iso_3166_1": "GB", "name": "United Kingdom" }
  ],
  "release_date": "2010-07-15",
  "revenue": 825532764,
  "runtime": 148,
  "spoken_languages": [
    { "english_name": "English", "iso_639_1": "en", "name": "English" },
    { "english_name": "Japanese", "iso_639_1": "ja", "name": "日本語" },
    { "english_name": "French", "iso_639_1": "fr", "name": "Français" }
  ],
  "status": "Released",
  "tagline": "Your mind is the scene of the crime.",
  "title": "Inception",
  "video": false,
  "vote_average": 8.3,
  "vote_count": 32000
}
```



### Refine and make it beautiful.
- Should be clean.
- Look professional.
- Should demonstrate idea. 