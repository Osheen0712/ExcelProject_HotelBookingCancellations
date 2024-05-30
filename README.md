## Hotel Booking Cancellations Dashboard

# Project Overview
This Excel project provides a comprehensive analysis of hotel booking cancellations. The dataset includes various details about the bookings, such as the type of hotel, cancellation status, guest demographics, and more. The project comprises three main components:

Raw Data: The original dataset containing all the booking details.
Pivot Table: A summary table that aggregates the data for deeper insights.
Dashboard: A visual representation of the key metrics and trends.

# File Structure
The Excel file consists of the following sheets:

1. hotel_booking
This sheet contains the raw data of hotel bookings with the following columns:
 - hotel: Type of hotel (e.g., Resort Hotel, City Hotel)
 - is_canceled: Cancellation status (0 for not canceled, 1 for canceled)
 - arrival_date_year: Year of arrival
 - arrival_date_month: Month of arrival
 - stays_in_week_nights: Number of weeknights stayed
 - adults: Number of adults
 - children: Number of children
 - babies: Number of babies
 - Guest_type(new): Categorized guest type (e.g., Couples, Single, Family)
 - country: Country of the guest
 - reserved_room_type: Type of room reserved
 - assigned_room_type: Type of room assigned
 - Room_status(new): Status of the room (Desired or Undesired)
 - reservation_status: Final status of the reservation (e.g., Check-Out, Canceled)

2. pivot
This sheet contains a pivot table summarizing the booking data. Key fields include:
 - Row Labels: Categorized data points such as guest type and hotel type.
 - Total Guests: Total number of guests in each category.
 - Cancelled_bookings: Number of canceled bookings in each category.
 - Count of hotel: Count of bookings per hotel type.

3. Dashboard
This sheet is intended for visual representations (charts, graphs) to highlight key insights from the data. Currently, it is empty and can be customized based on your requirements.

# How to Use
 - Data Exploration: Start by exploring the hotel_booking sheet to understand the raw data.
 - Data Aggregation: Use the pivot sheet to see aggregated data that provides insights into cancellation patterns.
 - Visualization: Customize the Dashboard sheet to create visualizations such as bar charts, pie charts, and trend lines to represent key metrics.

# Customization
You can customize this project based on your specific needs:
 - Adding Filters: Use Excel's filtering options to narrow down data by specific criteria (e.g., year, month, hotel type).
 - Creating Charts: Insert various charts in the Dashboard sheet to visualize trends and patterns.
 - Advanced Analysis: Use Excel formulas and functions to perform more advanced analysis.

# Conclusion
This Excel project provides a structured approach to analyze hotel booking cancellations. By leveraging the raw data, pivot table, and customizable dashboard, you can gain valuable insights into booking patterns and cancellation behaviors.
