def city_search(search_item, cities = ["New York", "Shanghai", "Munich", "Tokyo"] ):
    for city in cities:
        print("We are checking:",city)
        if city.lower() == search_item.lower():
            return True
        else:
            # go to the next item
            pass
    # no more items in list
    return False

# a list of cities
visited_cities = ["New York", "New Delhi", "Munich", "Tokyo", "Dubai", "Toronto", "Vancouver", "Chandigarh"]
nearby_cities=["Montreal","Ottawa","Quebec city"]
search = input("enter a city visited: ")

# Search the default city list
print(search, "in default cities is", city_search(search),"\n")

# search the list visited_cities using 2nd argument
print(search, "in visitied_cities list is", city_search(search,visited_cities),"\n")

print(search, "in nearby_cities list is", city_search(search,nearby_cities),"\n")
