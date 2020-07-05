# SQL-final-project
My final project from my SQL programming class at UCSD Extension


All questions below use the Chinook database paired with Microsoft SQL Server. 

1. Provide a report displaying the 10 artists with the most sales from July 2011 through June 2012.
Do not include any video tracks in the sales. Display the Artist's name and the total sales for the
year. Include ties for 10th if there are any.

2. Provide a report displaying the total sales for all Sales Support Agents grouped by year and
quarter. Include data from January 2010 through June 2012. Each year has 4 Sales Quarters
divided as follows:
  Jan-Mar: Quarter 1
  Apr-Jun: Quarter 2
  Jul-Sep: Quarter 3
  Oct-Dec: Quarter 4
The Sales Quarter column should display its values as First, Second, Third, Fourth. The data
needs to be ordered by the employee name, the fiscal year, and the sales quarter. The sales
quarter order should be numeric and not alphabetical (e.g. “Third” comes before “Fourth”).

3. The Sales Reps have discovered duplicate Playlists in the database. Some but not all of the
Playlists have Tracks associated with them. The duplicates have the same Playlist name, but
have a higher Playlist ID. Write a report that displays the duplicate Playlist IDs and Playlist
Names, as well as any associated Track IDs if they exist. Your result set will be marked for
deletion so it must be accurate.

4. Management would like to view Artist popularity by Country. Provide a report that displays the
Customer country and the Artist name. Determine the total number of tracks sold by an artist
to each country, and the total unique tracks by artist sold to each country. Include a column
that shows the difference between the track count and the unique track count. Include the total
revenue which will be the cost of the track multiplied by the number of tracks purchased.
Include a column that shows whether the tracks are audio or video (Hint: Videos have a
MediaTypeId =3). The range of data will be between July 2009 and June 2013. Order the results
by Country, Track Count and Artist Name.

5. HR wants to plan birthday celebrations for all employees in 2016. They would like a list of
employee names and birth dates, as well as the day of the week the birthday falls on in 2016.
Celebrations will be planned the same day as the birthday if it falls on Monday through Friday. If
the birthday falls on a weekend then the celebration date needs to be set on the following
Monday. Provide a report that displays the above date logic. The column formatting needs to
be the same as in the example below.

6. Management is interested in consolidating the Media Types and Genres offered. Specifically
they want to see which Genres and Media Types are underperforming in terms of Track sales.
Provide a report that groups Media Type and Genre. Include a column that shows the Unique
Track Count of available tracks, as well as a column called Tracks Purchased Count that shows
the count of tracks purchased. Include a column called Total Revenue for track purchases.
Include a column called Percentile dividing Track Purchases Count by Unique Track Count and
showing it as a percentile. Only include rows that have less than 10 in Total Revenue, or have a
Percentile of less than 50. Order by Total Revenue in ascending order, Percentile in descending
order, and Genre in ascending order.
