# 3333
def errorcode(num):
      match num:
        case 500:
            print("intrenet server error")
        case 401:
            print("unauthorised")
        case 400:
            print("bad request")
        case 403:
            print("forbidden")
        case 404:
            print("not found")
        case 501:
            print("not implemented")
        case 502:
            print("service temporarily overloaded")
        case 503:
            print("service unavailable")
num=input("which number is it?")
quit()
