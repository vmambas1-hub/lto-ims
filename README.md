
# lto-ims
#This information system will be a Land Transportation Office (LTO) Information Management System, designed to support the recording and management of drivers, motor vehicles, registrations, and traffic violations in the Philippines. The system aims to simulate a simplified version of real-world LTO operations, emphasizing proper database design, data integrity, and efficient query processing.

#Initial setup is to identify the active user as an admin or a user. A user can only view several reports depending on their toggled parameters within the system. While an admin could provide an update to the current database of the system.

#The system fetch the active user's information using the login page:
#  1. It checks whether the active user is a user or an admin.
#  2. When there is a new user, A registration can be seen under the login panel.
 # 3. The system sorts out the additional page of admin panel after fetching that the current user is an admin, while the viewing page will only be available for the user.

#Here's what the Admin can do:
# 1. First, the admin can access the admin panel which hosts 3 sub panels, namely:
#        a. Adding a Record of a driver, Vehicle, Violation
#       b. Viewing the database which shows the Database records grouped into Drivers, Vehicle, Registration, and Violation. Within this sub panel, the admin has   the ability to delete specific records.
#         c. The admin can also limit the access to the system. User and admin registration is within the approval of the admin under the manage accounts sub panel.

#USER and ADMINS are capable of Viewing reports.
#  1. Report 1: View all registered drivers filtered by: License type, License status, Age range, Sex
#  2. Report 2: View all vehicles owned by a given driver.
#  3. Report 3:View all vehicles with expired registrations as of a given date.
#  4. Report 4:View all drivers with expired or suspended licenses.
#  5. Report 5:View all traffic violations committed by a given driver within a specified date range.
#  6. Report 6:View the total number of violations per violation type for a given year.
# 7. Report 7:View all vehicles involved in violations within a given city or region.
#





